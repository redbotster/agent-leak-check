# Agent Secret Leak Check

A free, **client-side** check for the ways an AI agent config can leak secrets into
model context, a transcript, or a log — the class of bug seen in Hermes, LangChain,
and others.

Paste a `config.yaml`, an MCP servers block, or the code that wires up your keys.
It flags: hardcoded credentials, env-interpolated secrets that get resolved into
context, credentials in URLs, and secrets sitting inside prompts.

**Nothing is uploaded.** The scan runs entirely in your browser — view source.

Live: https://redbotster.github.io/agent-leak-check/

Built by the team at [1Claw](https://1claw.xyz?utm_source=leakcheck&utm_medium=repo).
