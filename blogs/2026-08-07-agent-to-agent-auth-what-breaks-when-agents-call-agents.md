---
title: "Agent-to-Agent Auth: What Breaks When Agents Call Agents"
url: "https://mojoauth.com/blog/agent-to-agent-auth-what-breaks-when-agents-call-agents"
date: "2026-08-07"
feed_url: "https://mojoauth.com/blog/feed/"
---
We built a six-hop agent delegation chain and ran eight probes against it. A spec-complete verifier caught one. The delegation history grows on every request and RFC 8693 says the resource server MUST ignore all of it but the last actor — here is what actually breaks, and what to build instead.
