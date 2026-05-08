# xAI (xai)

xAI is an AI research lab founded by Elon Musk. The xAI API exposes Grok foundation models for chat, function calling, vision, voice, image generation, and video generation, alongside research outputs from the Colossus training supercluster.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/xai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=xai-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - AI, LLM, Foundation Models, Grok, Generative AI

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| xAI Chat Completions API | OpenAI-compatible Chat Completions interface for Grok models. |
| xAI Responses API | Responses API with reasoning, function calling, and built-in tools (Live Search, code execution). |
| xAI Images API | Text-to-image generation via Grok Imagine. |
| xAI Video Generation API | Text/image-to-video generation via Grok Imagine. |
| xAI Voice API | Realtime voice including TTS, STT, and bidirectional voice. |
| xAI Embeddings API | Text and multimodal embeddings for retrieval/search. |
| xAI Models API | Model catalog and capability metadata. |
| xAI Batch API | Asynchronous batch processing at 20-50% discount, no rate-limit consumption. |

## Common Properties

- [Website](https://x.ai/)
- [Documentation](https://docs.x.ai/)
- [Plans](plans/xai-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/xai-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/xai-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/xai-plans-pricing.yml` | Pay-as-you-go per-token pricing per model + Batch API discount + Enterprise. Per-model rates pending reconciliation. |
| Rate Limits | `rate-limits/xai-rate-limits.yml` | Per-team RPM/TPM enforced (429 throttled). Batch API does not count toward limits. Per-model values pending. |
| FinOps | `finops/xai-finops.yml` | FOCUS-aligned, usage-based meters: input/output/cached tokens, tool invocations, batch, image, video. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
