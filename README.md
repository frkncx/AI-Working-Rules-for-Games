# AI-Working-Rules-for-Games

Originally made for Unity-MCP work, it works for any model and is ready to paste into your favourite AI agent.

A rules file for AI coding assistants working in Unity. It sets explicit limits on what the assistant may change without your permission, how it proves a fix, and what it must ask about first.

## What the rules cover
 
- Scope: fix only what was asked. Report nearby problems instead of fixing them.
- Fixes: repair the failing mechanism. Do not add a second one beside it.
- Evidence: read the real data before naming a cause.
- Verification: code that has not been run is reported as unverified.
- State: one owner per variable, transform or file.
- Cleanup: after removing something, search for what it left behind and ask before deleting.
- Approval required: balance values, hand-configured editor settings, and deleting or overwriting files.
- Modelling: state triangle counts, propose before modelling, and stop after five minutes if stuck.

## How to use

Paste AI_WORKING_RULES.md into the assistant at the start of a session.
