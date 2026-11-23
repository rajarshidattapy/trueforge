---
'@truefoundry/trueforge-core': patch
---

Close the remote MCP client when the SDK gives up reconnecting, so the connection is marked closed and the next call reconnects.
