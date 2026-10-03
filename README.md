# Flash Sale AI Agent — Public Hackathon Demo

> **Flash builds brand context, not disconnected posts.**

Flash Sale AI Agent is a WhatsApp-first AI marketing agent for SMEs and marketing teams. It maintains an independent persistent context for each Brand and uses approved Brand information across recurring marketing work, while keeping human review and final decisions in control.

This repository is a **Public Hackathon Demo Client**, not the source code of the commercial Flash Production Agent. The live agent runs privately in Production; proprietary orchestration, prompts, state handling, data models, integrations, and other implementation details are intentionally excluded.

## Why this matters to SMEs

Small businesses often repeat the same work across briefing, copywriting, design, corrections, and publishing preparation while trying to keep Brand identity consistent. Flash reduces that repeated setup by reusing persistent approved Brand context rather than requiring Brand identity, preferences, and instructions to be reconstructed for every post.

The same approach supports local businesses, clinics, stores, multi-business owners, and marketing teams. For agencies, Flash can increase content-production capacity by reducing repetitive production work while keeping strategy, review, and client decisions with the human team.

## Owner-Observed Workflow Benchmark

In the owner's current observed workflow, reaching a usable image and content result for a comparable post previously took approximately **20–30 minutes**.

After a one-time Brand setup of approximately **4–6 minutes**, recurring post creation with Flash currently takes about **3 minutes** to reach generated content and image — an observed elapsed-time reduction of roughly **85–90%**, or approximately **17–27 minutes saved per post**.

These figures represent the owner's observed elapsed workflow time, not an industry benchmark, controlled scientific study, active human labor measurement, third-party verification, or guaranteed customer performance.

## Verified Hackathon MVP capabilities

At capability level, the current MVP demonstrates:

- a live WhatsApp-first agent;
- new, existing, and multiple Brands with independent Brand context;
- Brand onboarding and reuse of approved Brand information;
- logo/reference-image analysis and Brand color extraction with human review;
- AI image generation and image analysis;
- AI content/text generation;
- human review and regeneration/correction where appropriate;
- Wallet/Flashes behavior;
- continuity and recovery across recurring work;
- 9:16 Story output;
- selected contact information on creatives;
- a publication decision; and
- real Facebook publishing demonstrated on a controlled linked Page.

Customer-image-assisted creative generation and multi-image customer creative analysis are **not** claimed as completed Hackathon capabilities.

## Multi-Brand and accumulating Brand intelligence

Each Brand keeps its own approved identity, information, instructions, decisions, and relevant context. As useful approved Brand context and history accumulate, Flash can become increasingly Brand-aware and better reflect recurring Brand patterns and preferences.

This is persistent contextual learning and accumulation of Brand intelligence. It does **not** mean automatic foundation-model retraining, fine-tuning, model-weight learning, or autonomous self-training.

### Brand color extraction

Flash can analyze a Brand logo or reference image, propose a HEX color palette, present it for human review, and save the approved Brand colors to the Brand context.

## Human-in-the-loop

Flash uses AI for repetitive analysis, generation, and preparation, while the human remains responsible for Brand decisions, approval of proposed colors, reviewing creative/content, requesting regeneration or correction, and the final publication decision where applicable.

## Models used

- **OpenAI — GPT-6 Luna:** content/text generation.
- **GPT Image 2:** image generation and image analysis.

The public submission does not disclose prompts, API configuration, routing, model-selection logic, provider implementation, or orchestration.

## MVP economics

The current commercial unit is **30 Flashes for one completed post**, including image + content, the initial generation, and up to two additional generations — a maximum of three generations.

| Package | Flashes | Approved-post entitlement |
| --- | ---: | ---: |
| EGP 499 | 300 | Up to 10 posts |
| EGP 849 | 600 | Up to 20 posts |
| EGP 1,099 | 900 | Up to 30 posts |

For the 30-post package, EGP 1,099 / 30 is approximately **EGP 36.63 package price per approved-post entitlement**. This is not AI cost per post, total cost, profit, or margin.

**Observed MVP Estimate:** approximately **$0.07 / EGP 3.65 per complete generation**. If all three generations are used, the theoretical three-generation scenario is approximately **$0.21 / EGP 10.96–11 per completed post**. These are observed MVP estimates, not final accounting cost, total operating cost, profit, or margin.

Up to 30 approved posts can represent approximately one post per day for 30 days as an example usage pattern; this is not a guaranteed monthly publishing service or a guarantee of 30 Facebook publications.

## Facebook Publishing — Hackathon Scope

Facebook publishing has been demonstrated successfully on a controlled linked Page using the real Flash publishing path.

Public self-service connection of arbitrary external customer Facebook Pages is deferred pending Meta access, verification, and review requirements. Flash does not simulate or fake publishing.

## Current vs Post-Hackathon

**Current verified:** live WhatsApp agent, new/existing/multiple Brands, independent Brand context, Brand onboarding/context, logo/reference-image color extraction, GPT Image 2 image generation and image analysis, GPT-6 Luna content/text generation, human review, Wallet/Flashes, continuity/recovery, 9:16 Story output, selected contact information on creative, publication decision, and controlled Facebook publishing.

**Current / accumulating:** explicit user instructions, approved Brand context, approved Brand identity/colors, reuse of accumulated approved context, and increasingly Brand-aware behavior as useful context grows.

**Post-Hackathon:** stronger long-term pattern analysis with larger history, customer-image-assisted creative generation, up-to-three customer-image creative analysis, arbitrary external Facebook Page self-service, paid ads, additional marketing channels, and advanced financial analytics/security/abuse controls.

## Quick Start for Judges

1. Open `demo/index.html` in a browser.
2. Select **Launch Flash on WhatsApp**, or scan the public QR code.
3. WhatsApp opens the public Flash entry with `ابدأ` prefilled.
4. Send the message and interact directly with the live Flash Production Agent.
5. Use the README, demo video, and impact slides for bounded evidence such as controlled Facebook publishing where needed.

No Meta configuration, Google configuration, database setup, API keys, or backend deployment is required from the judge.

## Public / private boundary

The public repository contains only a static reviewer-facing Demo Client, approved public branding, and high-level documentation. The static HTML/CSS does **not** implement the Flash agent.

The live system is the **Flash Production Agent reached through WhatsApp**. Production implementation remains proprietary and outside the public submission boundary.

See:

- `docs/architecture.md` — high-level public boundary.
- `docs/security-boundary.md` — public/private disclosure boundary.
- `assets/README.md` — public asset-governance rules.
- `docs/submission-form-answer-pack.md` — evidence-bounded submission-form material.
