# Unified Naming Convention
aka UNC, is an organization between executor developers to provide a unified scripting API for our scripters.

Basically UNC fucking sucks and it shouldn't exist but Roblox (probably years ago) made an update to break some checks by either updating their LuaVM (debug.getstack) or just rewriting their code entirely (getscriptclosure) and it made it so the UNC test would NEVER show 100% (no matter what)

## Checking your environment

You can run the UNC environment checking script to see how well your executor environment supports the UNC standard. Find the script [here.](UNCCheckEnv.lua) The script determines what is missing, and writes the results to file under workspace.
