# Public Asset Governance

This directory is reserved for future Hackathon assets that are separately reviewed and explicitly approved for public use.

No image, QR, screenshot, metric graphic, video frame, export, or other evidence asset should be added merely because it exists in Production.

Before an asset is added, it must pass both privacy review and intellectual-property review.

## Allowed only after review

Examples of potentially acceptable future assets include:

- approved Flash branding;
- an approved public QR that points only to the public user-facing entry;
- sanitized product screenshots;
- approved public architecture artwork that remains at capability level;
- verified aggregate impact visuals.

## Never include

Do not add assets that reveal or contain:

- credentials, tokens, secrets, cookies, or authentication material;
- customer names, phone numbers, IDs, message IDs, or personal data;
- raw webhook payloads;
- internal filesystem paths;
- private source code;
- debug or diagnostic screens;
- database rows or implementation-specific data relationships;
- internal state names or transitions;
- detailed conversation maps;
- proprietary question ordering or branching logic;
- prompts or prompt fragments;
- internal service, repository, orchestration, recovery, or asset-resolution logic.

A screenshot can leak implementation knowledge just as source code can. Sanitization therefore includes protection of both privacy and proprietary execution knowledge.
