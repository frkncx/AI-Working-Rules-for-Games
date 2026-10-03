# AI-Working-Rules-for-Games

Rules I give an AI coding assistant before it touches a Unity project. They keep it from changing code I did not ask about, and from calling a fix done before it has run.
 
Originally made for Unity-MCP work, they are not tied to one model and work with any assistant.
 
## How to use
 
Paste `AI_WORKING_RULES.md` at the start of a session. If your tool reads a rules file, save it there instead. Claude Code reads `CLAUDE.md`.
 
## What is in it
 
The rules cover what the assistant may change, how it proves a fix, and who owns each piece of state. They also list what it may never touch without asking, such as balance values and anything I set up by hand in the editor, and they set limits for 3D modelling.
