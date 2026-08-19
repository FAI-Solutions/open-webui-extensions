# FAI-Solutions Open WebUI Extensions Hub

**Practical filter, function, pipeline, and tool extensions for Open WebUI** — solving everyday usability and functionality gaps in local and cloud LLM workflows.

⚠ **Early stage** — currently featuring two extension, with additional releases planned as interest grows.

---

## 📦  Available Extensions

| Extension | Type | Version | Marketplace | Description |
| --- | --- | --- | --- | --- |
| [LLMTrace](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/llmtrace) | Filter | v1.2 | <a href="https://openwebui.com/posts/llmtrace_shows_the_llm_workflow_4dde62fe" rel="me noopener">⬇️ Install</a> | Visualizes the LLM workflow step-by-step |
| [Ollama Usage Monitor](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/ollama-usage-monitor) | Filter | v1.0 | <a href="https://openwebui.com/posts/4c6e3d6b-e65a-4c10-99a9-d9b4a75176c3" rel="me noopener">⬇️ Install</a> | Shows weekly Ollama Cloud usage stats |


<br>

## Why this hub exists

Open WebUI is a great chat interface, but it still has a few rough edges and minor annoyances. This repository collects **small, focused, high-quality extensions** designed to improve everyday usability.

**Planned extensions** (suggestions welcome!):
- [ ] LLMTrace v1.3 (ability to trace all new features added in open webui v0.11)
- [ ] ...

<br>

## Extension Details

### <picture><img src="assets/llmtrace.svg" width="20" alt="LLMTrace icon"></picture> LLMTrace

[LLMTrace](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/llmtrace) is an Open WebUI filter extension that gives insights into the LLMs workflow. It show each step that happens after the LLM receives Users query.

- Install directly from Open WebUI's <a href="https://openwebui.com/posts/llmtrace_shows_the_llm_workflow_4dde62fe" rel="me noopener">⬇️ Marketplace</a> or from [⬇️ Github](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/llmtrace/llmtrace.json)
- Full setup guide → [LLMTrace README](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/llmtrace)

Two different outputs are available (a compact timeline and a detailed dashboard).


### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/ollama-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/ollama-light.svg"><img src="assets/ollama-light.svg" width="16" alt="Ollama icon"></picture> Ollama Usage Monitor

[Ollama Usage Monitor](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/ollama-usage-monitor) is an Open WebUI filter extension that shows session & weekly Ollama Cloud usage stats at the top of each LLM response, including the time remaining until reset and the used models.

- Install directly from Open WebUI's <a href="https://openwebui.com/posts/4c6e3d6b-e65a-4c10-99a9-d9b4a75176c3" rel="me noopener">⬇️ Marketplace</a> or from [⬇️ Github](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/ollama-usage-monitor/ollama_usage_monitor.json)
- Full setup guide → [Ollama Usage Monitor README](https://github.com/FAI-Solutions/open-webui-extensions/tree/main/ollama-usage-monitor)

**Example output**
```bash
Account Name: Weekly 0% → Reset 3 days. • Session 0% → Reset 2 hours.
```

---

## 🤝 Contributing

Want to request an extension or add your own?  
- Open an issue with your idea (or just email me)
- Or submit a PR with a new folder following the same structure as the already existing extensions


## Contact

- **Developer**: Johannes Faber — [fais.udder466@passinbox.com](mailto:fais.udder466@passinbox.com)
- **Hub-Website**: <a href="https://fai-solutions.github.io/" rel="me noopener">https://fai-solutions.github.io/</a>

## License

[MIT](LICENSE)
