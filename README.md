# Awesome-Graphql-Security

## Top GraphQL Security Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on GraphQL API Protection, Query Cost Limits, Schema Security, Runtime Defense & API Security Testing*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **GraphQL Security**. These systems protect GraphQL APIs against abuse (deep nesting, batching, introspection leaks), enforce query cost and depth limits, discover schema risks, and provide runtime or testing-time defense for GraphQL endpoints.



**Examples** include Escape, Wallarm, 42Crunch, Noname Security, Traceable AI, Inigo, Cequence, Salt Security, Imperva API Security, and Akamai API Protector (the category leaders).



**Open-source emphasis**: Full enterprise GraphQL security platforms are mostly commercial. Practical open options include **GraphQL Armor**, **GraphQL Protect**, **GraphQL Shield**, and related middleware and testing tools. This section lists the strongest available open resources.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Escape](https://escape.tech/)**  

  GraphQL-focused security platform offering continuous testing, discovery, and protection tailored to GraphQL APIs and schemas.



- **[Wallarm](https://www.wallarm.com/)**  

  API security platform with GraphQL support for runtime protection, threat detection, and API attack prevention.



- **[42Crunch](https://42crunch.com/)**  

  API security platform that audits, tests, and governs GraphQL (and OpenAPI) contracts with security quality gates in CI/CD.



- **[Noname Security](https://nonamesecurity.com/)**  

  API security platform providing discovery, posture management, and runtime protection that includes GraphQL APIs.



- **[Traceable AI](https://www.traceable.ai/)**  

  API security and observability platform with deep context for GraphQL and other API styles, focused on threat detection and risk.



- **[Inigo](https://inigo.io/)**  

  GraphQL-specific security and observability platform for schema governance, rate limiting, and runtime protection of GraphQL services.



- **[Cequence Security](https://www.cequence.ai/)**  

  API security platform addressing bot and abuse protection across API surfaces including GraphQL endpoints.



- **[Salt Security](https://salt.security/)**  

  API security platform focused on discovery, posture, and runtime protection for modern APIs including GraphQL.



- **[Imperva API Security](https://www.imperva.com/)**  

  Enterprise API security offering that protects GraphQL and REST APIs as part of a broader application security portfolio.



- **[Akamai API Protector / API Security](https://www.akamai.com/)**  

  Edge and API security capabilities from Akamai that can protect GraphQL endpoints as part of broader API and web protection.



## Open-Source GitHub Projects

- **[GraphQL Armor](https://github.com/Escape-Technologies/graphql-armor)**  

  Leading open-source security middleware for Apollo, Yoga, and Envelop servers—limits depth, cost, aliases, batching, and other GraphQL-specific risks (MIT).



- **[GraphQL Protect](https://github.com/ldebruijn/graphql-protect)**  

  Open-source security proxy compatible with any HTTP GraphQL server or gateway—persisted operations, depth/alias limits, field suggestion blocking, and more.



- **[GraphQL Shield](https://github.com/maticzav/graphql-shield)**  

  Open-source permission and authorization layer for GraphQL schemas, helping enforce fine-grained access control rules.



- **[graphql-eslint](https://github.com/dimaMachina/graphql-eslint)**  

  Open-source ESLint plugin for GraphQL schemas and operations—useful for catching security-relevant patterns in CI.



- **[InQL and GraphQL security testing helpers](https://github.com/)**  

  Open tools (e.g., Burp extensions and scanners) for introspection analysis and security testing of GraphQL APIs you own.



- **[GraphQL Cop and similar CI security tests](https://github.com/)**  

  Open utilities that run common GraphQL security checks suitable for continuous integration pipelines.



- **[Persisted / trusted documents open patterns](https://github.com/)**  

  Open implementations and libraries for allowing only pre-approved GraphQL operations (persisted queries).



- **[Query complexity / cost analysis open libraries](https://github.com/)**  

  Libraries that compute and enforce GraphQL query complexity scores for Apollo and other servers.



- **[Awesome GraphQL Security lists](https://github.com/Escape-Technologies/awesome-graphql-security)**  

  Curated open collections of GraphQL security tools, middleware, and resources.



- **[WAF and reverse-proxy rules for GraphQL](https://github.com/)**  

  Open configurations and modules that apply GraphQL-aware filtering at the edge or proxy layer.



### Additional Strong Open-Source Options

- Deploying **GraphQL Armor** as the first line of defense on Apollo or Yoga servers.

- Putting **GraphQL Protect** in front of any GraphQL gateway for language-agnostic protection.

- Combining open middleware with commercial API security platforms for discovery and advanced threat detection.

- Enforcing **persisted operations** and disabling introspection in production as baseline hygiene.

- Accepting that continuous discovery, behavioral runtime detection, and enterprise-scale API inventories still favor commercial platforms (Escape, Wallarm, 42Crunch, Salt, Traceable, Inigo, etc.).

- Focusing open-source efforts on query hardening, cost control, and shifting security left into CI.



**Frameworks for building custom systems**: Harden servers with GraphQL Armor or equivalent → enforce trusted documents → lint schemas and operations in CI with graphql-eslint → optionally front with GraphQL Protect or a commercial API security layer → monitor with open telemetry. Suitable for teams running self-hosted GraphQL. Most enterprises pair open hardening with commercial API security platforms for full coverage.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- GraphQL security tools help reduce risk but do not replace secure schema design, authorization, or overall API security practice. Misconfiguration can leave APIs exposed. This list is not security advice.



---

**Made for API security engineers, GraphQL developers, and platform teams protecting modern APIs.**

Let's keep GraphQL APIs resilient, well-governed, and as open as practical.
