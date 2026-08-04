# DeepSeek (deepseek)

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
