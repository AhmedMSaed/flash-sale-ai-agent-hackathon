# Public / Private Security Boundary

The Hackathon repository is deliberately separated from the commercial Production implementation.

## Public side

The public submission may contain:

- the minimal static demo client;
- high-level project explanation;
- deliberately public links used to reach the live product;
- approved public branding;
- sanitized evidence that is separately reviewed before publication;
- verified aggregate impact evidence when available.

## Private side

The following remain outside the public repository:

- credentials and secrets;
- customer and operational data;
- Production runtime code;
- proprietary conversation and state design;
- prompts and prompt construction;
- persistence and repository implementation;
- internal services and orchestration;
- database implementation details;
- private AI, Meta, Google, and other integration implementation;
- security and operational internals.

## Runtime behavior of the public demo

The public demo client performs no AI calls, no database access, no Meta Graph API calls, no Google API calls, no Production authentication, and no proxying to private services.

The reviewer reaches the live agent only through an explicit user-facing WhatsApp launch action.

The purpose of this boundary is to make the submission understandable and testable without publishing the proprietary execution recipe for Flash.
