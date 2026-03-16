# OAuth 2.0 First-Party Native Authorization for AI Agents via Structured Elicitation

**Document:** `draft-embesozzi-oauth-fipa-agent-elicitation`  
**Status:** Individual Submission — Informational  
**Author:** Martin Besozzi (TwoGenIdentity)  
**Date:** 2026-03-09

## Abstract

This document defines a Structured Elicitation extension to the OAuth 2.0
First-Party Applications (FiPA) specification, establishing a standard
metadata format for FiPA authorization challenge responses. FiPA intentionally
leaves authenticator metadata out of scope: the format in which the
authorization server describes available authenticators and the inputs they
require is undefined. This gap prevents interoperable implementation by AI
Agents and other non-browser clients.

The extension defines a transport-agnostic Structured Elicitation mechanism.
Model Context Protocol (MCP) Elicitation serves as the normative runtime
binding; a non-normative binding for HTTP-based AI Agent APIs is also
provided. The scope covers two strong authenticator types: Authenticator
Apps (TOTP) and Passkeys (WebAuthn). Non-normative guidance for Third-Party
and First-Party AI Agent deployment patterns is included.

## Documents

| Document | Link |
|----------|------|
| **Draft** | [draft-oauth-fipa-agent-elicitation.html](https://embesozzi.github.io/draft-embesozzi-oauth-fipa-agent-elicitation/draft-oauth-fipa-agent-elicitation.html) |

## Versions

| Date | Link |
|------|------|
| **Latest** | [Editor's Copy](https://embesozzi.github.io/draft-embesozzi-oauth-fipa-agent-elicitation/draft-oauth-fipa-agent-elicitation.html) |

## Contributing

Feedback is welcome via GitHub Issues or Pull Requests.

## Author

Martin Besozzi — [TwoGenIdentity](https://twogenidentity.com) —
embesozzi@twogenidentity.com

---

*This document is an independent submission Internet-Draft for community discussion. It is not an IETF or OpenID Foundation standards-track document.*

