# figma-rest-api-spec

> This is a fork of [figma/rest-api-spec](https://github.com/figma/rest-api-spec) with extended types.
> Type adjustments made in this fork are also planned to be requested upstream to the original repository.

This repository contains the OpenAPI specification and Typescript types for the [Figma REST API](https://www.figma.com/developers/api).

[Changelog](https://www.figma.com/developers/api#changelog)

Note: this specification is currently in beta. If you notice any inaccuracies with the specification, please [file an issue](https://github.com/figma/rest-api-spec/issues) in the original repository.

## Usage

The OpenAPI (v3.1.0) specification is located in the `openapi/` directory. This specification can be used with a [wide variety of tools](https://tools.openapis.org/) to generate API documentation, client SDKs, and more.

## Notes on this fork

In this fork, **only `openapi.yaml` is updated**. The method for generating `dist/` (TypeScript types) from the original repository is unknown, so the `dist/` directory is not maintained here.
