# Santiago Andrés Aragón Guzmán

[Español](README.es.md)

**AI Engineer & Senior Database Architect | Applied AI Systems (RAG, AST Firewalls, Multi-Agent Orchestration) · Enterprise Databases (Oracle PL/SQL, PostgreSQL)**

🌐 **[Explore my interactive portfolio](https://andresaragon.github.io/)**

## About me

Senior Backend & Data Engineer at Open Intelligence with 5+ years building PL/SQL and Oracle systems for payment collection automation and debt negotiation. I reduced query latency by an estimated ~45% by optimizing query hints and cut integration errors by an estimated ~30%. I apply this database foundation to applied AI solutions, including Text-to-SQL assistants with RAG, LLM pipelines, and multi-agent orchestration with Claude Code. Based in Cali, Colombia, and available for international remote roles as a contractor or EOR.

## Key highlights

- 5+ years in enterprise database architecture and query optimization across Oracle PL/SQL and PostgreSQL.
- 1,085 automated tests passing in the flagship `text-to-sql-rag` pipeline.
- 245+ SQL injection and DoS attempts blocked by a deterministic AST semantic firewall.
- Production multi-agent orchestration using the Maker-Checker protocol and Orca ADE.

## Projects

- [text-to-sql-rag](https://github.com/andresaragon/text-to-sql-rag): Text-to-SQL assistant with schema RAG (pgvector) and an AST SQL firewall (sqlglot) that supports PostgreSQL 16 and Oracle 23c Free; its deterministic AST firewall has blocked 245+ injection and DoS attempts, and fail-fast startup dropped from 138s to 4s. The pipeline has 1,085 passing tests; Python, FastAPI (MIT license). Measured, not assumed: [what an Oracle firewall has to catch](https://github.com/andresaragon/text-to-sql-rag/blob/main/docs/articles/oracle-sql-firewall.md) and an [A/B benchmark of Postgres vs Oracle vs transpiled SQL](https://github.com/andresaragon/text-to-sql-rag/blob/main/docs/benchmarks/2026-10-23-ab.md).
- [plsql-lens](https://github.com/andresaragon/plsql-lens): PL/SQL analysis in Python: inventory and call graph, review rules with SARIF output, utPLSQL test generation, a seeded benchmark, and Oracle-to-PostgreSQL migration findings and rewrites checked against both databases; Python, Typer (MIT license). Its reports include what does not hold, for example [five inputs that break the parser's "never raises, quickly" claim](https://github.com/andresaragon/plsql-lens/blob/main/docs/reports/robustness.md).
- [job-autoapply](https://github.com/andresaragon/job-autoapply): Next.js and Supabase job application platform with a job aggregator, hybrid AI (Ollama, Claude, Gemini), ATS form autofill, a Chrome extension, and n8n and Telegram webhooks (TypeScript, MIT license).
- [mrgames-web](https://github.com/andresaragon/mrgames-web): e-commerce store for video games and subscriptions built with Next.js and Supabase, in production: https://mrgames.com.co
- [FinanzasIA](https://github.com/andresaragon/FinanzasIA): personal finance project with AI built with TypeScript (MIT license).

## Private projects

- **TrueGuard** (private repo): native Android app (Kotlin and Jetpack Compose) for call spam blocking with a Supabase backend.
- **orquestador-plugin** (private repo): Claude Code plugin that acts as a technical lead and delegates code to worker CLIs with maker-checker review.
- **AI video pipeline** (private repo): produces videos for the active YouTube channels **Founder Digital** and **The Silicon Auditor**, with Gemini scripts, Whisper subtitles, and n8n orchestration with human approval.

## Contact

- [Portfolio](https://andresaragon.github.io/)
- [LinkedIn](https://www.linkedin.com/in/santiagoaragonguzman)
