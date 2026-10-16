
## 🚀 Quick start

```bash
git clone https://github.com/ajeetg123/Awesome-MCP-Servers.git
cd Awesome-MCP-Servers/weather

uv sync              # or: pip install -r requirements.txt
uv run weather.py
```

Then point an MCP client at it. With Claude Code:

```bash
claude mcp add weather -- uv --directory /absolute/path/to/Awesome-MCP-Servers/weather run weather.py
```
