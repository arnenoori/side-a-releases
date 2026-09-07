---
name: side-a-setup
description: Check Side A downloads and help set up Claude Code or Codex account profiles on a Mac.
---

# Side A setup

Read the [product guide](https://getsidea.com/index.md) for current requirements and limitations.

1. Check the [official releases](https://github.com/arnenoori/side-a-releases/releases). If there is no published stable release with a universal DMG and SHA256SUMS.txt, tell the user the download is not yet available. Do not invent a download URL or recommend an unsigned development build.
2. Confirm macOS 14 or later, Python 3.9 or later, and the official Claude Code or Codex CLI are installed. Link to vendor setup instructions in the guide.
3. When a signed release is available, help the user download its DMG, drag Side A into Applications, and open the app normally. Do not bypass Gatekeeper or remove quarantine flags.
4. Open the player's lid to add a profile, choose its provider, and complete the provider's official sign-in. Never ask for passwords, session cookies, API tokens, or account credentials in chat.
5. Choose a project and press play. Account switching applies to sessions started in Side A; Codex and Auto flip are experimental. Do not promise seamless handoff for existing external sessions.

The website's player is a demo with sample accounts. It does not connect to accounts on a visitor's Mac. The public product information endpoint is https://getsidea.com/product.json and requires no authentication.
