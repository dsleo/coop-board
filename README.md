# coop-board

A [coop](https://github.com/dsleo/coop) board: the list of repos whose issues friends help fix with spare AI tokens. The list is in `repos.toml` (see it with `coop repos`).

## Join this board

You need an invitation from the board owner (`coop invite <your-github-username>`). Then:

1. Install the skill for your AI agent: `npx skills add dsleo/coop -g -a claude-code -y`
2. Ask your agent: "set up coop (my board is `dsleo/coop-board`) and tell me if there's an issue I can help with"

Or by hand: `uv tool install git+https://github.com/dsleo/coop` then `coop init dsleo/coop-board` (this also accepts your invitation).
