# npm (npm)
npm is the world's largest software registry, hosting over two million JavaScript packages for the Node.js ecosystem. Their developer platform provides APIs for searching and retrieving package metadata, managing access tokens, subscribing to registry event webhooks, and publishing packages with supply chain provenance verification.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Packages, JavaScript, Node.js, Package Management, Registry, Security

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### npm Registry API
The npm Registry API provides programmatic access to the npm package registry, the largest software registry in the world hosting over two million JavaScript packages. Developers can query package metadata, download tarballs, search for packages, and retrieve version-specific information. The API follows CouchDB-based conventions and serves package manifests in JSON format, enabling tools and services to integrate with the npm ecosystem for dependency resolution, package discovery, and automated workflows.

**Human URL:** [https://github.com/npm/registry/blob/main/docs/REGISTRY-API.md](https://github.com/npm/registry/blob/main/docs/REGISTRY-API.md)


#### Tags:

 - Packages, JavaScript, Registry, Package Management, Node.js

#### Properties

- [Documentation](https://github.com/npm/registry/blob/main/docs/REGISTRY-API.md)
- [OpenAPI](openapi/npm-registry-api-openapi.yml)

### npm Public API
The npm Public API provides authenticated endpoints for managing npm access tokens, configuring trusted publishers, and exchanging OIDC tokens for short-lived registry access. It supports creating, listing, and deleting npm access tokens with customizable permissions, scope restrictions, expiration settings, and CIDR IP range limitations. The API also enables CI/CD providers like GitHub Actions, GitLab CI, and CircleCI to publish packages securely through OIDC token exchange without requiring long-lived npm tokens.

**Human URL:** [https://api-docs.npmjs.com/](https://api-docs.npmjs.com/)


#### Tags:

 - Packages, Tokens, Authentication, Security, OIDC, Access Control

#### Properties

- [Documentation](https://api-docs.npmjs.com/)
- [OpenAPI](openapi/npm-public-api-openapi.yml)

### npm Hooks API
The npm Hooks API allows developers to subscribe to notifications about changes in the npm registry. Hooks send HTTP POST payloads to a configured URI whenever a package is changed, enabling developers to build integrations that respond to registry events in real time. Users can add hooks to follow specific packages, track all activity of given npm users, or monitor all packages within an organization or user scope. The API provides endpoints for creating, listing, updating, and deleting hook subscriptions.

**Human URL:** [https://blog.npmjs.org/post/145260155635/introducing-hooks-get-notifications-of-npm](https://blog.npmjs.org/post/145260155635/introducing-hooks-get-notifications-of-npm)


#### Tags:

 - Webhooks, Notifications, Events, Automation, Packages

#### Properties

- [Documentation](https://blog.npmjs.org/post/145260155635/introducing-hooks-get-notifications-of-npm)
- [OpenAPI](openapi/npm-hooks-api-openapi.yml)
- [AsyncAPI](asyncapi/npm-hooks-asyncapi.yml)

### npm CLI
The npm CLI is the official command-line interface for the npm package manager, providing developers with tools to install, publish, and manage JavaScript packages and their dependencies. It supports package publishing with provenance attestation via Sigstore, workspace management for monorepos, script execution, semantic versioning, and comprehensive dependency tree management. The CLI is bundled with Node.js and serves as the primary developer interface for interacting with the npm registry.

**Human URL:** [https://docs.npmjs.com/cli](https://docs.npmjs.com/cli)


#### Tags:

 - Command Line, Package Management, JavaScript, Node.js, Developer Tools

#### Properties

- [Documentation](https://docs.npmjs.com/cli)
- [Source Code](https://github.com/npm/cli)

### npm Provenance
npm Provenance provides supply chain security for JavaScript packages by establishing a verifiable link between a published package and its source code repository and build environment. When a package is published with provenance, it is signed using Sigstore public good servers and the attestation is logged in a public transparency ledger. This allows developers to verify where and how a package was built before downloading it, helping to protect against supply chain attacks and ensuring the integrity of the npm ecosystem.

**Human URL:** [https://docs.npmjs.com/generating-provenance-statements](https://docs.npmjs.com/generating-provenance-statements)


#### Tags:

 - Security, Supply Chain, Verification, Sigstore, Transparency, CI/CD

#### Properties

- [Documentation](https://docs.npmjs.com/generating-provenance-statements)
- [Documentation](https://github.blog/security/supply-chain-security/introducing-npm-package-provenance/)

## Common Properties

- [Portal](https://www.npmjs.com/)
- [Documentation](https://docs.npmjs.com/)
- [Blog](https://blog.npmjs.org/)
- [Login](https://www.npmjs.com/login)
- [Support](https://www.npmjs.com/support)
- [PrivacyPolicy](https://docs.npmjs.com/policies/privacy)
- [TermsOfService](https://docs.npmjs.com/policies/terms)
- [Website](https://www.npmjs.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
