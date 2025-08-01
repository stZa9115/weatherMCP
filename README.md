powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

{
  "mcpServers": {
    "weather": {
      "command": "C:\\Users\\s9706\\.local\\bin\\uv.exe",
      "args": [
        "--directory",
        "D:\\localMCP\\weather",
        "run",
        "weather.py"
      ]
    }
  }
