# xAI (xai)

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
