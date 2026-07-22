# Claude

Claude is an Anthropic-backed assistant for Cinatra chat. Mention it in a workspace conversation and it answers, reasons over your request, and drives the tools and skills available to it to get the work done. It runs locally on the Cinatra host runtime and resolves Anthropic model access through the connected Anthropic connector, so no API keys are ever handled by this package.

## Works with

- Anthropic

## Capabilities

- Answer questions and hold a conversation in Cinatra chat under the `claude` tag
- Reason over a request and use the tools and skills available to it to complete the work
- Run locally on the host runtime with Anthropic as the preferred model provider
- Resolve Anthropic credentials through the Anthropic connector — never through this package
