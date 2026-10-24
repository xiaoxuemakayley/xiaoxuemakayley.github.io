---
title: "Understanding Bugs in Model Context Protocol Development Frameworks: An Empirical Study"
date: 2026-09-15 00:00:00 +0800
selected: true
pub: "ACM Transactions on Software Engineering and Methodology (TOSEM)"
pub_date: "2026"
abstract: >-
  As the Model Context Protocol (MCP) becomes foundational for LLM integrations, framework-level bugs can propagate to downstream applications. This paper presents the first large-scale empirical study of 535 resolved bugs across four widely used MCP frameworks (FastMCP, Go SDK, Python SDK, and TypeScript SDK). We find that common symptoms include negotiation, execution, and deployment failures, primarily caused by framework implementation defects and protocol violations. Furthermore, our evaluation of LLM-based automated repair shows that providing MCP protocol knowledge significantly improves repair effectiveness, increasing the Resolve Rate to up to 69.5% and collectively resolving 81.3% of all bugs across configurations.
authors:
  - "Sicheng He"
  - "Chang Li"
  - "Jiaming Liu"
  - "Jin Liu"
  - "Jacky Keung"
  - "Xiaoxue Ma#"
links:
  Paper: "https://doi.org/10.1145/3847119"
---