SHAG Starter repository (demo wallet + CI)
=========================================

What is inside:
- shag-wallet-demo/   : demo Qt6 wallet (UI + C++ backend simulation)
- .github/workflows/  : Windows build workflow (GitHub Actions) to build .exe and run windeployqt
- monero-fork-scaffold/: place to begin configuring Monero fork (templates + notes)

Quick start (push to GitHub):
1. Create a new repo on GitHub (e.g. 'shag-coin') and clone it locally.
2. Copy content of this archive into the repo folder.
3. git add . && git commit -m "Initial SHAG starter" && git push origin main
4. Open Actions tab on GitHub; the workflow will run and produce artifact shag-wallet-windows (zip)

Notes:
- The Monero fork is not included; forking Monero requires cloning the full Monero repo and applying patches.
- This starter is intended to let you quickly build and test the wallet UI and CI flow.
