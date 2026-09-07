# GMXAuto

This repository contains [OpenAPI](https://www.openapis.org/) descriptions for a reference implementation of the [Geoprise GM-X Auto OpenAPI Bridge](https://github.com/geoprise/GMXAuto) to fully connect the GM-X Enterprise Resources Planning (ERP) application and agentic artificial intelligence (AI).

## What is OpenAPI?

From the [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification):

> The OpenAPI Specification (OAS) defines a standard, programming language-agnostic interface description for HTTP APIs, which allows both humans and computers to discover and understand the capabilities of a service without requiring access to source code, additional documentation, or inspection of network traffic. When properly defined via OpenAPI, a consumer can understand and interact with the remote service with a minimal amount of implementation logic. Similar to what interface descriptions have done for lower-level programming, the OpenAPI Specification removes guesswork in calling a service.

## What is the GM-X Auto OpenAPI Bridge?

The Model Context Protocol (MCP) harnesses reasoning, planning, and decision-making capabilities of frontier large language models (LLMs) such as Anthropic Claude, Microsoft Copilot, Google Gemini, and OpenAI ChatGPT by reliably connecting autonomous AI agents to application programming interface (API) endpoints exposed by Web applications.

MCP gives LLMs a way to discover, rationalize, and interact with Web applications including mission-critical ERP software. The business opportunity driving the adoption of LLMs is the automation of repetitive, tedious data entry and reporting tasks using AI agents.  

MCP is today’s universal standard for connecting AI agents to APIs. Any API that is documented according to the OAS (formerly known as the Swagger Specification) can be transformed automatically into functional MCP servers that expose the API as a tool to LLM Applications such as Claude Desktop. Transformation is done using popular MCP generator services including Postman, Speakeasy Gram, liblab, Prefect FastMCP, and Stainless. Self-hosted generators such as the open-source openapi-mcp-generator are also available.

Each tool visible and available to an LLM Application has a title, description, and input schema which AI agents can discover and interpret to create natural-language requests. The MCP server converts those requests into API calls which activate specific Web application functions that generate and return the results to the AI agent.

The GM-X Auto OpenAPI Bridge exposes every one of nearly 3,900 GM-X ERP functions, screens, and reports to MCP servers through 453 OAS-compatible APIs requiring no proprietary middleware or custom-coded wrappers.  

## Project Status

As of Version 11.3.0 release, this description is considered **stable** and generally available.  

## Description Formats

Each OpenAPI document is available in **bundled** format.

The bundled descriptions are single file artifacts that make usages of OpenAPI **components** for reuse and portability. This is the preferred way of interacting with Geoprise GM-X Auto OpenAPI descriptions.

## Contributing

Because this description is used across the entire Geoprise API development experience, we don't currently accept pull requests that directly modify the description. This repository is automatically kept up to date with the description used to validate Geoprise GM-X Auto API requests.

If you've identified a mismatch between the behavior of any API and these descriptions, or found an issue with the format of a schema, [please open an issue.](mailto:support@geoprise.com)
## License

github/GMXAuto is licensed under the [GNU Affero General Public License v3.0](https://github.com/geoprise/GMXAuto/blob/main/LICENSE)
