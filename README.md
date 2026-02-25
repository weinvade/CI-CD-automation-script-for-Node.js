🚀 Node CI/CD Pipeline Automation (Bash)
A lightweight Bash-based CI/CD automation script for Node.js projects.
This tool validates the environment, installs dependencies safely, runs lint checks, builds the project, and deploys it — all with strict error handling and clean logging.

Features
    • ✅ Strict Bash mode (set -euo pipefail)
    • ✅ Dependency validation (Node.js & npm)
    • ✅ Safe installation (npm ci support)
    • ✅ Lint verification
    • ✅ Build execution
    • ✅ Deployment execution
    • ✅ Structured error logging
    • ✅ Graceful CTRL+C handling

Requirements
    • Node.js
    • npm
    • package-lock.json must exist
    • A valid package.json with relevant scripts:
        ◦ build
        ◦ deploy
        ◦ (optional) lint
Check your versions:
node -v
npm -v
