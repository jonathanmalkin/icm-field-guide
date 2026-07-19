# SkillOpt

- **Pattern:** method optimization; not itself an ICM application pattern
- **Forms:** evaluation Pipeline over versioned skill records
- **Repeating unit:** an evaluation run against one skill version
- **ICM application:** fixed test set → run → judge → compare → proposed edit →
  human review → versioned promotion.
- **Boundary:** prevent evaluation leakage and keep the human owner responsible
  for changes to method or behavior.
- **Evidence:** public Microsoft Research paper; adjacent skill-optimization
  research, not an ICM implementation.
- **Source:** [SkillOpt: Executive Strategy for Self-Evolving Agent
  Skills](https://arxiv.org/abs/2605.23904)
