---
"effect": patch
---

Add `NetAddress.SocketAddress.Input` and checked and unsafe constructors for normalizing concrete socket address configuration. `HttpServer.make` now accepts these input forms while continuing to expose a canonical `SocketAddress`.
