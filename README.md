# metronome-plugins

Public plugins and skills for working with Metronome from AI agents, including the Metronome MCP server.

Status: scaffold. Plugins will be added under `plugins/`; the marketplace manifest is `.claude-plugin/marketplace.json`.

## Use (Claude Code)
```
/plugin marketplace add process-metronome/metronome-plugins
/plugin install <plugin>@metronome-plugins
```

## Contributing
Each plugin lives in `plugins/<name>/` with its own `.claude-plugin/plugin.json`, skills in `skills/<skill>/SKILL.md`, and a README. Never commit tokens, tenant data or internal URLs.

License: MIT.
