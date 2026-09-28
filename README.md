# google-oauth-certs-mirror

Mirror of Google's public OpenID Connect signing keys (JWKS), refreshed every 6 hours by a scheduled GitHub Action.

- Source: https://www.googleapis.com/oauth2/v3/certs
- Mirror: `jwks.json` in this repository

These are **public** keys published by Google for verifying Google ID tokens. No secrets are stored here.
Consumers should still verify `iss`, `aud` and `exp` on every token and keep a last-known-good copy.
