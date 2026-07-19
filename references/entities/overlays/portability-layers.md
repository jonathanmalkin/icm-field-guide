# Portability layers

- **Trigger:** rules or workflows repeat across projects, domains, clients, or runtimes.
- **Platform layer:** conventions that apply across nearly every project.
- **Domain layer:** references shared by a meaningful project family.
- **Workspace layer:** instance-specific facts and working artifacts.
- **Rule:** point upward to shared references; never move client facts upward.
- **Human check:** owners approve changes whose blast radius crosses workspaces.
- **Removal test:** keep a reference local until more than one real consumer
  needs the same maintained source.
- **Role model:** Reusable Workflows Guide.
