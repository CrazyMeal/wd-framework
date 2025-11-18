# WD Marketplace

Official marketplace for Web Development plugins - React, Next.js, Vue, TypeScript and more.

## 🚀 Quick Start

Install via Claude Code:

```bash
/plugin marketplace add Para-FR/wd-framework
```

Then restart Claude Code to activate the plugins.

## 📦 Available Plugins

### WD Framework v2.0

Intelligent web development framework with 22 specialized commands, 5 expert agents, and 11 AI personas.

**Key Features:**
- 22 specialized commands for web development
- 5 expert agents (frontend, backend, security, test, docs)
- 11 AI personas for domain-specific intelligence
- Smart MCP coordination (Context7, Sequential, Magic, Playwright)
- Auto-routing and wave orchestration

[📖 Full Documentation →](plugins/wd/README.md)

## 📁 Repository Structure

```
wd-framework/
├── .claude-plugin/           # Marketplace configuration
│   └── marketplace.json      # Plugin registry
├── plugins/                  # Plugin implementations
│   └── wd/                  # WD Framework plugin
│       ├── .claude-plugin/  # Plugin metadata
│       ├── agents/          # 5 specialized agents
│       ├── commands/        # 22 slash commands
│       ├── docs/            # Documentation
│       ├── examples/        # Usage examples
│       └── README.md        # Plugin documentation
└── README.md                # This file
```

## 🛠️ Technologies

React, Next.js, Vue, Angular, TypeScript, Tailwind CSS, Node.js, Python, and more...

## 📄 License

MIT © Para CC-France

## 🤝 Contributing

Contributions are welcome! Please read the [plugin development guide](plugins/wd/docs/PLUGIN_DEVELOPMENT.md) for details.
