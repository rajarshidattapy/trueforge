---
'@truefoundry/trueforge-core': patch
---

Only treat remote MCP errors that say the session is missing or expired as session expiry, so unrelated errors that mention "session" no longer reset the connection and retry the call.
