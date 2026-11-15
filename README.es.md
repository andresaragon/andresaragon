# Santiago Andrés Aragón Guzmán

[English](README.md)

**Ingeniero de IA & Arquitecto Senior de Bases de Datos | Sistemas de IA Aplicada (RAG, Cortafuegos AST, Orquestación Multiagente) · Bases de Datos Empresariales (Oracle PL/SQL, PostgreSQL)**

🌐 **[Explora mi portafolio interactivo](https://andresaragon.github.io/)**

## Sobre mí

Ingeniero Senior de Backend y Datos en Open Intelligence con más de 5 años construyendo y optimizando sistemas PL/SQL y Oracle de misión crítica para automatización de cobro y negociación de deuda. Analicé y optimicé más de 70 planes de ejecución complejos, hints de consulta e índices compuestos en procesos por lotes, y estandaricé modelos de migración e interfaces API para minimizar fallas de integración. Aplico esa experiencia en bases de datos a soluciones de IA aplicada como asistentes Text-to-SQL con RAG, pipelines de LLM y orquestación multi-agente con Claude Code. Vivo en Cali, Colombia, y me encuentro disponible para roles remotos internacionales como contratista o EOR.

## Logros destacados

- Más de 5 años en arquitectura de bases de datos empresariales y optimización de consultas con Oracle PL/SQL y PostgreSQL.
- 1.085 pruebas automatizadas aprobadas (89 omitidas) en el pipeline insignia `text-to-sql-rag`.
- Más de 245 casos de prueba de seguridad adversariales validados contra un cortafuegos semántico AST determinista.
- Flujos de orquestación multiagente estructurados con el protocolo Maker-Checker y Orca ADE.

## Proyectos

- [text-to-sql-rag](https://github.com/andresaragon/text-to-sql-rag): asistente Text-to-SQL con RAG sobre el esquema (pgvector) y un firewall SQL con AST (sqlglot) con soporte para PostgreSQL 16 y Oracle 23c Free; su cortafuegos AST determinista valida más de 245 vectores de ataque adversariales, y la respuesta fail-fast ante base de datos inalcanzable bajó de 138,5 s a 4,0 s. El pipeline tiene 1.085 pruebas aprobadas; Python, FastAPI (licencia MIT). Medido, no supuesto: [qué debe detectar un firewall para Oracle](https://github.com/andresaragon/text-to-sql-rag/blob/main/docs/articles/oracle-sql-firewall.es.md) y un [benchmark A/B de Postgres, Oracle y SQL transpilado](https://github.com/andresaragon/text-to-sql-rag/blob/main/docs/benchmarks/2026-10-23-ab.es.md).
- [plsql-lens](https://github.com/andresaragon/plsql-lens): análisis de PL/SQL en Python: inventario y grafo de llamadas, reglas de revisión con salida SARIF, generación de tests utPLSQL, un benchmark con semilla y hallazgos y reescrituras de migración de Oracle a PostgreSQL comprobados contra las dos bases de datos; Python, Typer (licencia MIT). Sus informes incluyen lo que no se sostiene, por ejemplo [cinco entradas que rompen la afirmación «nunca lanza, y rápido» del parser](https://github.com/andresaragon/plsql-lens/blob/main/docs/reports/robustness.md).
- [job-autoapply](https://github.com/andresaragon/job-autoapply): plataforma Next.js y Supabase de postulación a empleos con agregador de vacantes, IA híbrida (Ollama, Claude, Gemini), autollenado de formularios ATS, extensión de Chrome y webhooks con n8n y Telegram (TypeScript, licencia MIT).
- [mrgames-web](https://github.com/andresaragon/mrgames-web): tienda web de videojuegos y suscripciones de negocio propio con Next.js y Supabase, en producción: https://mrgames.com.co
- [FinanzasIA](https://github.com/andresaragon/FinanzasIA): proyecto de finanzas personales con IA en TypeScript (licencia MIT).

## Proyectos privados

- **TrueGuard** (repo privado): app Android nativa (Kotlin y Jetpack Compose) anti-spam de llamadas con backend en Supabase.
- **orquestador-plugin** (repo privado): plugin de Claude Code que actúa como líder técnico y delega código a CLIs trabajadores con revisión maker-checker.
- **Pipeline de video con IA** (repo privado): produce videos para los canales activos de YouTube **Modo Fundador Digital** y **El Auditor de Silicio**, con guiones en Gemini, subtítulos con Whisper, ensamblaje con n8n y aprobación humana antes de gastar en generación de pago.

## Contacto

- [Portafolio](https://andresaragon.github.io/)
- [LinkedIn](https://www.linkedin.com/in/santiagoaragonguzman)
