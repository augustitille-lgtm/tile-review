# Tile Review
AI-powered academic research and econometric evaluation framework.

## Use with Claude Code
Open this repository as a project in Claude Code. Place an authorized manuscript in the project or supply its accessible path. Run `/review-paper manuscript.pdf` (or provide the manuscript path and target journal). The project command is stored in `.claude/commands/review-paper.md`.

## Use with ChatGPT or another AI assistant
Upload the manuscript and REVIEW-INSTRUCTIONS.md, and ask the assistant to follow the instructions. No API keys are included.

## Scope
Ten review stages and a verification pass. Independent agents are conditional on the host's capabilities; this repository does not implement a standalone multi-agent runtime. No empirical validation or live Claude Code test has been performed. AI feedback is advisory. Verify citations and results independently. Do not commit confidential manuscripts or datasets to a public repository.

## Publishing
Create a GitHub repository named `tile-review`, extract this package and upload its contents, including the hidden `.claude` directory. The repository URL will be https://github.com/YOUR-USERNAME/tile-review after publication.
