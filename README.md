# DeepSeek (deepseek)

DeepSeek is an artificial intelligence company that provides advanced large language models accessible through an API that is compatible with the OpenAI and Anthropic SDKs. The DeepSeek API offers chat completions, fill-in-the-middle completions, function calling, JSON output, streaming, multi-turn conversations, context caching, and a thinking/reasoning mode for complex problem solving.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- Chat
- Chat Completion
- LLM
- Large Language Models
- Reasoning
- Code Completion

## Timestamps

- **Created:** 2025-01-27
- **Modified:** 2026-05-29

## APIs

### DeepSeek Chat Completion API

Creates a model response for a given chat conversation. Supports the deepseek-chat and deepseek-reasoner models with options for tool calling, JSON output, streaming, temperature, top-p, frequency and presence penalties, and stop sequences. Compatible with the OpenAI Chat Completions request and response shapes.

- **Human URL:** [https://api-docs.deepseek.com/api/create-chat-completion](https://api-docs.deepseek.com/api/create-chat-completion)
- **Base URL:** `https://api.deepseek.com`

#### Tags

- AI
- Artificial Intelligence
- Chat
- Chat Completion
- LLM

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/create-chat-completion)
- [OpenAPI](openapi/deepseek-chat-completion-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepseek-chat-completion-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepseek-chat-completion-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/deepseek-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Rules](rules/deepseek-chat-completion-api-rules.yml)
- [Capabilities](capabilities/deepseek-chat-completion-api-capabilities.yml)

### DeepSeek Fill-In-The-Middle (FIM) Completion API

Beta endpoint that performs fill-in-the-middle completions where a prompt and an optional suffix are provided and the model fills the gap. Useful for code completion and inline code generation tasks.

- **Human URL:** [https://api-docs.deepseek.com/guides/fim_completion](https://api-docs.deepseek.com/guides/fim_completion)
- **Base URL:** `https://api.deepseek.com/beta`

#### Tags

- AI
- Artificial Intelligence
- Code Completion
- Fill-In-The-Middle
- FIM

#### Properties

- [Documentation](https://api-docs.deepseek.com/guides/fim_completion)
- [OpenAPI](openapi/deepseek-fim-completion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepseek-fim-completion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepseek-fim-completion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/deepseek-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Rules](rules/deepseek-fim-completion-rules.yml)
- [Capabilities](capabilities/deepseek-fim-completion-capabilities.yml)

### DeepSeek List Models API

Lists the currently available DeepSeek models, providing basic information about each one such as the model identifier, owner, and availability.

- **Human URL:** [https://api-docs.deepseek.com/api/list-models](https://api-docs.deepseek.com/api/list-models)
- **Base URL:** `https://api.deepseek.com`

#### Tags

- AI
- Artificial Intelligence
- Models

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/list-models)
- [OpenAPI](openapi/deepseek-lists-models-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepseek-lists-models-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepseek-lists-models-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/deepseek-lists-models-api-rules.yml)
- [Capabilities](capabilities/deepseek-lists-models-api-capabilities.yml)

### DeepSeek User Balance API

Returns the current account balance for the authenticated DeepSeek user, including available credit and currency. Useful for monitoring spend and gating workloads programmatically.

- **Human URL:** [https://api-docs.deepseek.com/api/get-user-balance](https://api-docs.deepseek.com/api/get-user-balance)
- **Base URL:** `https://api.deepseek.com`

#### Tags

- AI
- Artificial Intelligence
- Balance
- Billing
- Pricing

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/get-user-balance)
- [OpenAPI](openapi/deepseek-user-balance-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepseek-user-balance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepseek-user-balance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Rules](rules/deepseek-user-balance-api-rules.yml)
- [Capabilities](capabilities/deepseek-user-balance-api-capabilities.yml)

## Common Properties

- [GitHub Organization](https://github.com/deepseek-ai)
- [LinkedIn](https://www.linkedin.com/company/deepseek-ai)
- [Documentation](https://api-docs.deepseek.com/)
- [Pricing](https://api-docs.deepseek.com/quick_start/pricing)
- [Authentication](https://api-docs.deepseek.com/quick_start/token_usage)
- [Rate Limits](https://api-docs.deepseek.com/quick_start/rate_limit)
- [Errors](https://api-docs.deepseek.com/quick_start/error_codes)
- [Status Page](https://status.deepseek.com/)
- [F A Q](https://api-docs.deepseek.com/faq)
- [Changelog](https://api-docs.deepseek.com/updates)
- [Website](https://www.deepseek.com/)
- [Privacy Policy](https://chat.deepseek.com/downloads/DeepSeek%20Privacy%20Policy.html)
- [Terms of Service](https://chat.deepseek.com/downloads/DeepSeek%20Terms%20of%20Use.html)
- [JSON-LD](json-ld/deepseek-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/deepseek-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
