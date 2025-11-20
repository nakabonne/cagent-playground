# cagent-playground

https://github.com/docker/cagent

## Install to Apple silicon

```
curl -Lo cagent https://github.com/docker/cagent/releases/download/v1.9.10/cagent-darwin-arm64
chmod +x cagent
sudo mv cagent /usr/local/bin/
```

## Examples

### Analyze logs with TUI

```
cagent run agents/log_analyzer.yaml -a root
```

## Summarize news once

```
cagent exec --model openai/gpt-4o agents/news_notion_agent.yaml
```
