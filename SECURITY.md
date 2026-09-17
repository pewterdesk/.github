# Security Policy

Pewterdesk is non-custodial: it never holds funds and doesn't run a backend that touches your keys. That doesn't mean there's no attack surface — key storage, signing, and exchange auth are exactly the parts we take most seriously.

## Reporting a vulnerability

If you find a security issue — anything involving API key handling, wallet signing, key storage, or a way the app could leak or misuse credentials — please **do not open a public GitHub issue**.

Instead, email: security@<my-domain>

Please include:
- What you found and why it's exploitable
- Steps to reproduce
- Impact (what an attacker could do with it)

We'll acknowledge reports within a few days and credit reporters (if wanted) once a fix ships.

## Scope

In scope: the desktop app, the exchange adapters, key storage/signing code, and the (future) web build's proxy layer.

Out of scope: the exchange's own infrastructure (Hyperliquid, etc.) — report those directly to the exchange.
