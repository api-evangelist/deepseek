# DeepSeek (deepseek)

DeepSeek is an artificial intelligence company that provides advanced large language models accessible through an API that is compatible with the OpenAI and Anthropic SDKs. The DeepSeek API offers chat completions, fill-in-the-middle completions, function calling, JSON output, streaming, multi-turn conversations, context caching, and a thinking/reasoning mode for complex problem solving.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/deepseek/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **x-type:** company
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI, Artificial Intelligence, Chat, Chat Completion, LLM, Large Language Models, Reasoning, Code Completion

## Timestamps

- **Created:** 2025-01-27
- **Modified:** 2026-04-28

## APIs

### DeepSeek Chat Completion API

Creates a model response for a given chat conversation. Supports the deepseek-chat and deepseek-reasoner models with options for tool calling, JSON output, streaming, temperature, top-p, frequency and presence penalties, and stop sequences.

- **Base URL:** https://api.deepseek.com
- **Human URL:** https://api-docs.deepseek.com/api/create-chat-completion

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/create-chat-completion)
- [OpenAPI](openapi/deepseek-chat-completion-api-openapi.yml)
- [Rules](rules/deepseek-chat-completion-api-rules.yml)
- [Capabilities](capabilities/deepseek-chat-completion-api-capabilities.yml)

### DeepSeek Fill-In-The-Middle (FIM) Completion API

Beta endpoint that performs fill-in-the-middle completions where a prompt and an optional suffix are provided and the model fills the gap. Useful for code completion and inline code generation tasks.

- **Base URL:** https://api.deepseek.com/beta
- **Human URL:** https://api-docs.deepseek.com/guides/fim_completion

#### Properties

- [Documentation](https://api-docs.deepseek.com/guides/fim_completion)
- [OpenAPI](openapi/deepseek-fim-completion-openapi.yml)
- [Rules](rules/deepseek-fim-completion-rules.yml)
- [Capabilities](capabilities/deepseek-fim-completion-capabilities.yml)

### DeepSeek List Models API

Lists the currently available DeepSeek models, providing basic information about each one such as the model identifier, owner, and availability.

- **Base URL:** https://api.deepseek.com
- **Human URL:** https://api-docs.deepseek.com/api/list-models

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/list-models)
- [OpenAPI](openapi/deepseek-lists-models-api-openapi.yml)
- [Rules](rules/deepseek-lists-models-api-rules.yml)
- [Capabilities](capabilities/deepseek-lists-models-api-capabilities.yml)

### DeepSeek User Balance API

Returns the current account balance for the authenticated DeepSeek user, including available credit and currency. Useful for monitoring spend and gating workloads programmatically.

- **Base URL:** https://api.deepseek.com
- **Human URL:** https://api-docs.deepseek.com/api/get-user-balance

#### Properties

- [Documentation](https://api-docs.deepseek.com/api/get-user-balance)
- [OpenAPI](openapi/deepseek-user-balance-api-openapi.yml)
- [Rules](rules/deepseek-user-balance-api-rules.yml)
- [Capabilities](capabilities/deepseek-user-balance-api-capabilities.yml)

## Common Properties

- [Documentation](https://api-docs.deepseek.com/)
- [Pricing](https://api-docs.deepseek.com/quick_start/pricing)
- [Authentication](https://api-docs.deepseek.com/quick_start/token_usage)
- [Rate Limits](https://api-docs.deepseek.com/quick_start/rate_limit)
- [Errors](https://api-docs.deepseek.com/quick_start/error_codes)
- [Status](https://status.deepseek.com/)
- [FAQ](https://api-docs.deepseek.com/faq)
- [ChangeLog](https://api-docs.deepseek.com/updates)
- [Website](https://www.deepseek.com/)
- [Privacy Policy](https://chat.deepseek.com/downloads/DeepSeek%20Privacy%20Policy.html)
- [Terms of Service](https://chat.deepseek.com/downloads/DeepSeek%20Terms%20of%20Use.html)
- [JSON-LD](json-ld/deepseek-context.jsonld)
- [Vocabulary](vocabulary/deepseek-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
