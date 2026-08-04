# xAI (xai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

xAI is an AI research lab founded by Elon Musk. The xAI API exposes Grok foundation models for chat, function calling, vision, voice, image generation, and video generation, alongside research outputs from the Colossus training supercluster.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/xai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/xai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Foundation Models
- Grok
- Generative AI

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### xAI Chat Completions API

Generates conversational completions using Grok foundation models, including multi-turn conversations, function calling, structured outputs, and reasoning. OpenAI-compatible Chat Completions interface.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Chat
- Completions
- LLM
- Grok

#### Properties

- [Documentation](https://docs.x.ai/docs/overview)
- [API Reference](https://docs.x.ai/docs/api-reference#chat-completions)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Responses API

The Responses API supports text generation, multi-turn conversations, reasoning, tool/function calling, and built-in tools (Live Search, code execution).

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Responses
- LLM
- Grok
- Reasoning

#### Properties

- [Documentation](https://docs.x.ai/docs/api-reference#responses)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Images API

Generates images from text prompts using the Grok Imagine image models. OpenAI-compatible image generation endpoint.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Images
- Generation
- Multimodal

#### Properties

- [Documentation](https://docs.x.ai/docs/guides/image-generations)
- [API Reference](https://docs.x.ai/docs/api-reference#image-generations)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Video Generation API

Generates video from text or image inputs using the Grok Imagine video models, with editing and detailed control options.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Video
- Generation
- Multimodal

#### Properties

- [Documentation](https://docs.x.ai/docs/guides/video-generation)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Voice API

Realtime voice API supporting speech-to-text, text-to-speech, and bidirectional realtime voice interaction with Grok.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Voice
- Speech
- Audio
- Realtime

#### Properties

- [Documentation](https://docs.x.ai/docs/guides/voice)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/xai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### xAI Embeddings API

Generates vector embeddings of text and other inputs for retrieval, classification, and semantic search workflows.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Embeddings
- Vector

#### Properties

- [Documentation](https://docs.x.ai/docs/guides/embeddings)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Models API

Lists available Grok models, model capabilities, context windows, and metadata.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.x.ai/docs/api-reference#models)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xAI Batch API

Submits offline batch jobs of chat or embedding requests at a discount (20-50% off standard rates), with results returned out-of-band. Batch requests do not count toward rate limits.

- **Human URL:** [https://docs.x.ai/docs/api-reference](https://docs.x.ai/docs/api-reference)
- **Base URL:** `https://api.x.ai/v1`

#### Tags

- Batch
- Async

#### Properties

- [Documentation](https://docs.x.ai/docs/guides/batch)
- [OpenAPI](openapi/xai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/xai-org)
- [LinkedIn](https://www.linkedin.com/company/x-ai)
- [Website](https://x.ai/)
- [Documentation](https://docs.x.ai/)
- [Plans](plans/xai-plans-pricing.yml)
- [Rate Limits](rate-limits/xai-rate-limits.yml)
- [Fin Ops](finops/xai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
