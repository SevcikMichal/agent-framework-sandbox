# Agent Framework Sandbox

Minimal sandbox for Microsoft Agent Framework using a local LLM client.

Prerequisites
- .NET SDK
- Optional: a local Ollama or compatible endpoint

Configuration
- `OLLAMA_ENDPOINT` (optional) — defaults to `http://127.0.0.1:11434/v1`
- `MODEL_NAME` (optional) — default model name used by the sample

Run

```bash
dotnet run --project agent-framework-sandbox.csproj
```

Notes
- This is a small demo; modify `Program.cs` to experiment with agents and workflows.
