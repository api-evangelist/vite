# Vite

Next-generation frontend build tool providing a lightning-fast dev server using native ES modules and an optimized production build via Rolldown. Vite's JavaScript and Plugin APIs enable deep programmatic integration for framework authors, build toolchain maintainers, and IDE plugin developers.

**Human URL:** https://vitejs.dev  
**Documentation:** https://vite.dev/guide/  
**GitHub Org:** https://github.com/vitejs  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/apis.yml

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Build Tools, Bundler, Development Server, ESM, Frontend, Hot Module Replacement, JavaScript, Plugin API, TypeScript, Vite

## APIs

### Vite JavaScript API

Programmatic interface for embedding Vite into build toolchains and custom CLI tools — createServer, build, preview, resolveConfig, and file transforms.

**Human URL:** https://vite.dev/guide/api-javascript

#### Properties

- [Documentation](https://vite.dev/guide/api-javascript)
- [OpenAPI](openapi/vite-javascript-api-openapi.yml)

---

### Vite Plugin API

Lifecycle hooks for extending Vite's build pipeline, dev server configuration, HTML transformation, and hot module replacement.

**Human URL:** https://vite.dev/guide/api-plugin

#### Properties

- [Documentation](https://vite.dev/guide/api-plugin)
- [OpenAPI](openapi/vite-plugin-api-openapi.yml)

---

## OpenAPI Specifications

| File | Description |
|---|---|
| [vite-javascript-api-openapi.yml](openapi/vite-javascript-api-openapi.yml) | Dev server endpoints, configuration schemas, and transform result types |
| [vite-plugin-api-openapi.yml](openapi/vite-plugin-api-openapi.yml) | Plugin hook schemas, HMR update payloads, and module graph types |

## Spectral Rules

| File | Description |
|---|---|
| [vite-rules.yml](rules/vite-rules.yml) | Spectral ruleset enforcing Vite API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | APIs |
|---|---|
| [shared/javascript-api.yaml](capabilities/shared/javascript-api.yaml) | Vite JavaScript API |

### Workflow Capabilities

| File | Description |
|---|---|
| [frontend-build.yaml](capabilities/frontend-build.yaml) | Unified REST + MCP interface for frontend dev and build workflows |

## JSON Schema

| File | Description |
|---|---|
| [vite-inline-config-schema.json](json-schema/vite-inline-config-schema.json) | JSON Schema for the Vite InlineConfig object |

## JSON Structure

| File | Description |
|---|---|
| [vite-inline-config-structure.json](json-structure/vite-inline-config-structure.json) | Field-level structure for ViteInlineConfig |

## JSON-LD Context

| File | Description |
|---|---|
| [vite-context.jsonld](json-ld/vite-context.jsonld) | Linked data context mapping Vite vocabulary to schema.org |

## Examples

| File | Description |
|---|---|
| [vite-javascript-api-create-server-example.json](examples/vite-javascript-api-create-server-example.json) | createServer() request and response |
| [vite-javascript-api-build-example.json](examples/vite-javascript-api-build-example.json) | build() production build request and output |

## Vocabulary

| File | Description |
|---|---|
| [vite-vocabulary.yml](vocabulary/vite-vocabulary.yml) | Canonical Vite terminology: HMR, Rolldown, ESM, plugin hooks |

## Common Properties

- [Website](https://vitejs.dev)
- [Documentation](https://vite.dev/guide/)
- [GitHub Organization](https://github.com/vitejs)
- [GitHub Repository](https://github.com/vitejs/vite)
- [Twitter](https://twitter.com/vite_js)
- [Discord](https://chat.vitejs.dev)
- [npm Package](https://www.npmjs.com/package/vite)
- [Changelog](https://github.com/vitejs/vite/blob/main/packages/vite/CHANGELOG.md)
- [License](https://github.com/vitejs/vite/blob/main/LICENSE)
- [Awesome Vite](https://github.com/vitejs/awesome-vite)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
