# n8n-claw Expert Agents

Expert agent personas for [n8n-claw](https://github.com/freddy-schuetz/n8n-claw) — the self-hosted AI agent system.

## Available Agents

| Agent | Category | Description | Based on |
|---|---|---|---|
| Research Expert | General | Web research, fact-checking, source evaluation | — |
| Content Creator | General | Text creation, social media, blog articles, marketing copy | — |
| Data Analyst | General | Data analysis, pattern recognition, structured reports | — |

## How It Works

Expert agents are specialized sub-agents that your main n8n-claw agent can delegate tasks to. Each agent has its own expertise profile that defines how it works and what quality standards it follows.

The main agent's personality stays unchanged — it delegates specific tasks to experts and rephrases their results in its own tone.

## Installation

Agents can be installed via the Agent Library tool in your n8n-claw agent:

```
"Install the Research Expert agent"
"Show me available expert agents"
"Remove the Data Analyst"
```

Or they ship pre-installed with `setup.sh`.

## Creating Your Own Agent

See [TEMPLATE_EXAMPLE.md](TEMPLATE_EXAMPLE.md) for a step-by-step guide.

## Attribution

Some agent personas may be inspired by or adapted from [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) (MIT License, 31k+ Stars). When an agent is based on a prompt from that repo, the `manifest.json` contains a `based_on` field with a link to the original, and the "Based on" column in the table above links to the source.

## License

MIT
