# Decision log (live-run)

| Decision | Choice | Why |
|----------|--------|-----|
| Showcase workflow | Spec-to-ship | Highest orchestration + Grok Bot showcase value |
| MVP artifact | Public GitHub repo | PR trail is the demo |
| Repo name | `grok-bot-spec-to-ship` | Locked by Orchestrator |
| Seats | Lead=Orchestrator, Builder3=Researcher, Product Designer=Product/Design, Builder02=Engineer, Builder01=Reviewer | Minimum effective roster |
| SoT | Notion + GitHub (not chat memory) | Anti context-pollution |
| Orchestration | Supervisor + parallel specialists + one Reviewer pass | Borrow CrewAI hierarchical / LangGraph supervisor; reject AutoGen free-for-all |
