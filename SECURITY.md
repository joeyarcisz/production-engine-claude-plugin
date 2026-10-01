# Security

## Reporting a vulnerability

Email **intake@production-engine.com** with "Security" in the subject, a description of the issue and steps to reproduce it. Please do not share details publicly until we have responded.

We will confirm we received your report and keep you updated until it is resolved.

## How the connection is protected

- **Sign-in, not keys.** Claude connects through OAuth with PKCE (S256). There is no API key or password to copy, and the plugin itself contains no credentials.
- **Owners and admins only.** Only a workspace owner or admin on an active or trial plan can approve a connection. A suspended member, a demoted role or a lapsed plan stops the connection on its next request.
- **One workspace per connection.** Every request is scoped to the workspace that approved it. A connection cannot see another company's data.
- **Least privilege.** Connections read by default. Starting a draft estimate is a separate permission the person must approve, and Claude asks before each one.
- **Limits.** Each connection has a request budget, and estimates started from an assistant are capped per workspace.
- **Revocable.** Owners and admins can see every connection and disconnect it at any time under Company Settings > Integrations.

More detail: [production-engine.com/security](https://production-engine.com/security)
