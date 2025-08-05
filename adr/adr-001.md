# ADR 001: Use Keycloak as the Identity Provider

## Status
Accepted

## Context
We need a robust and flexible identity provider to manage authentication and authorization for our internal services. The solution should support OAuth2, OpenID Connect, and SAML protocols.

## Decision
We will use Keycloak as our identity provider. It will be deployed locally using Docker during development and later moved to a managed environment for production.

## Consequences
- Developers can run Keycloak locally using Docker.
- Integration with other services will be simplified due to Keycloak's support for standard protocols.
- We need to manage Keycloak configurations and realm settings as part of our infrastructure.
