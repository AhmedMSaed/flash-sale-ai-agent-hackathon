# Public Architecture Boundary

This document intentionally stays at a high level. It describes only the public trust boundary required for the Hackathon submission.

```text
Reviewer
   ↓
Public Hackathon Demo Client
   ↓
WhatsApp
   ↓
Live Flash Production Agent
```

Production implementation remains proprietary and is outside the public submission boundary.

## Boundary meaning

- The public demo client is a static reviewer-facing surface.
- The reviewer explicitly chooses to open the existing public WhatsApp entry.
- The real agent behavior is demonstrated by the live Production Flash experience.
- Production implementation remains proprietary and outside this public submission.
