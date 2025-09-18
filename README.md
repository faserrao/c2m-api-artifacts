# C2M API Artifacts

This repository contains automatically generated artifacts from the [c2m-api-repo](https://github.com/faserrao/c2m-api-repo).

## ⚠️ Do Not Edit These Files

All files in this repository are automatically generated. Any manual changes will be overwritten by the next build.

To make changes, please edit the source files in [c2m-api-repo](https://github.com/faserrao/c2m-api-repo).

## Repository Structure

- `openapi/` - Generated OpenAPI specifications
- `postman/` - Postman collections and metadata
- `docs/` - API documentation
- `sdks/` - Generated client SDKs

## Build Status

Latest build: See [GitHub Actions](https://github.com/faserrao/c2m-api-repo/actions)

## Generated Files

### OpenAPI Specifications
- `openapi/c2mapiv2-openapi-spec-base.yaml` - Base spec generated from EBNF
- `openapi/c2mapiv2-openapi-spec-final.yaml` - Final spec with auth overlay applied
- `openapi/bundled.yaml` - Dereferenced version for tools that need inline schemas

### Postman Collections
- `postman/collections/` - Generated Postman collections
- `postman/metadata/` - Postman IDs, mock URLs, and configuration

### Documentation
- `docs/redoc/` - ReDoc interactive documentation
- `docs/swagger/` - Swagger UI documentation
- `docs/index.html` - Main documentation entry point

### SDKs
- `sdks/python/` - Python client library
- `sdks/javascript/` - JavaScript/Node.js client library
- `sdks/typescript/` - TypeScript client library
- Additional languages as configured

## Usage

### Accessing Documentation
- GitHub Pages: https://faserrao.github.io/c2m-api-artifacts/
- Or clone locally and open `docs/index.html`

### Using SDKs
Each SDK directory contains its own README with installation and usage instructions.

### Getting OpenAPI Spec
```bash
# Latest spec
curl https://raw.githubusercontent.com/faserrao/c2m-api-artifacts/main/openapi/c2mapiv2-openapi-spec-final.yaml
```

## License

See [c2m-api-repo](https://github.com/faserrao/c2m-api-repo) for license information.