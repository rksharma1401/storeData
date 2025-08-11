# Google Auth Local

This documentation provides an overview of the **Google OAuth 2.0 Identity Provider** configured for local development or testing.

## Overview

Google Auth Local is a service component that enables OAuth-based authentication using Google's identity platform. It is designed for local testing and development environments.

## Features

- OAuth 2.0 flow initiation  
- Token exchange and validation  
- User profile retrieval  
- Integration with Backstage catalog  
- CI/CD via CircleCI  
- TechDocs support

## APIs Provided

- `google-oauth-api`: Initiates OAuth flow and exchanges tokens  
- `google-token-validation-api`: Validates access tokens  
- `google-userinfo-api`: Retrieves user profile data

## Dependencies

- `google-oauth-client`: OAuth client library  
- `google-auth-sdk`: SDK for Google authentication

## CI/CD

This component uses CircleCI for continuous integration and deployment.

## Documentation

This site is generated using TechDocs and powered by MkDocs.
