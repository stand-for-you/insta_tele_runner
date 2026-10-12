# 🚀 Public Actions Runner (`insta_tele_runner`)

This repository serves as a dedicated, public GitHub Actions execution runner for the private Telegram bot application at [`stand-for-you/insta_tele`](https://github.com/stand-for-you/insta_tele).

### Architecture
- **Source Code**: 100% private in `stand-for-you/insta_tele`.
- **Compute Runner**: Runs in this public repository to utilize free, unlimited GitHub Actions runner minutes.
- **Security**: The runner repository contains zero application code. It fetches the private codebase ephemerally in-memory during workflow runs using an encrypted SSH Deploy Key (`PRIVATE_REPO_KEY`).
