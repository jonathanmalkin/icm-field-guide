# Orchestration threshold

- **Trigger:** a proposed design uses multiple agents, autonomous branching, or
  heavy runtime coordination.
- **ICM usually wins:** sequential knowledge work, explicit stage artifacts,
  low concurrency, and human review at boundaries.
- **Framework code may be justified:** genuine parallelism, dynamic branching,
  autonomous scale, transactional coordination, strict runtime isolation,
  multi-user conflict handling, or hard latency requirements.
- **Test:** can each supposed agent be replaced by a fresh session reading one
  folder contract and exact inputs?
- **Human check:** accept the operational burden before crossing the threshold.
- **Role model:** Multi-Agent Workspaces.
