---
title: "Which Authorization Flow Number Verification Actually Requires (and Why the Answer Changed)"
url: "https://mojoauth.com/blog/why-number-verification-uses-oidc-authorization-code-not-ciba"
date: "2026-09-02"
feed_url: "https://mojoauth.com/blog/feed/"
---
CAMARA Number Verification v2.1.0 permits authorization code, CIBA and JWT-Bearer. The real constraint is device identity and the access token's amr claim.
