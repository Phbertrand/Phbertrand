# ECC skills, agents and commands

Copied from https://github.com/affaan-m/ECC (v2.2.3, MIT licence — see ECC-LICENSE),
because `/plugin install` is not available in Claude Code cloud sessions.

Included: `skills/` (327), `agents/` (72), `commands/` (98).
Left out on purpose: ECC's hooks (Node scripts that would run on every edit and command).

Note: about 20 commands (e.g. /evolve, /sessions, /instinct-status, /auto-update) expect
ECC's own scripts folder via CLAUDE_PLUGIN_ROOT and won't fully work in this setup.
