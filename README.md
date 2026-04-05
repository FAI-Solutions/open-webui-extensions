# FAI-Solutions Open WebUI Extensions Hub

**Practical filter, function, pipeline, and tool extensions for Open WebUI** — solving everyday usability and functionality gaps in local and cloud LLM workflows.

⚠ **Early stage** — currently featuring one extension, with additional releases planned as interest grows.

---

## 📦  Available Extensions

| Extension | Type | Version | Marketplace | Description |
| --- | --- | --- | --- | --- |
| [Ollama Usage Monitor](/ollama-usage-monitor) | Filter | v0.5 | [⬇️ Install](https://openwebui.com/posts/4c6e3d6b-e65a-4c10-99a9-d9b4a75176c3) | Shows weekly Ollama Cloud usage stats |


## Why this hub exists

Open WebUI is a great chat interface, but it still has a few rough edges and minor annoyances. This repository collects **small, focused, high-quality extensions** designed to improve everyday usability.

**Planned extensions** (suggestions welcome!):
- [ ] Proper Debugger
- [ ] ...


## Extension Details

### <picture><source media="(prefers-color-scheme: dark)" srcset="assets/ollama-dark.svg"><source media="(prefers-color-scheme: light)" srcset="assets/ollama-light.svg"><img src="assets/ollama-light.svg" width="16" alt="Ollama icon"></picture> Ollama Usage Monitor

[Ollama Usage Monitor](/ollama-usage-monitor) is an Open WebUI filter extension that shows session & weekly Ollama Cloud usage stats at the end of each LLM response, including the time remaining until reset.

- Install directly from Open WebUI's [⬇️ Marketplace](https://openwebui.com/posts/4c6e3d6b-e65a-4c10-99a9-d9b4a75176c3)
- Full setup guide → [Ollama Usage Monitor README](/ollama-usage-monitor)

**Example output:**
```bash
------ ☁ Ollama Usage Monitor ------
| MyAccount: Weekly 29.3% - Reset 1 day • run 2.4% - Reset 5 hours |
```

---

## 🤝 Contributing

Want to request an extension or add your own?  
- Open an issue with your idea (or just email me)
- Or submit a PR with a new folder following the same structure as `ollama-usage-monitor`


## Contact

- **Developer**: Johannes Faber — [fais.udder466@passinbox.com](mailto:fais.udder466@passinbox.com)


## License

[MIT](LICENSE)
