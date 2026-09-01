---
"effect": patch
"@effect/sql-pg": patch
---

Add `effect/unstable/net/IpNetwork` for canonical IPv4 and IPv6 CIDR values, including strict host-bit validation, containment and overlap operations, exact address bounds and counts, and Schema string codecs. PostgreSQL `inet` and `cidr` encoding now share the strict network-address parser while continuing to accept bare `cidr` addresses with their full-width prefix.
