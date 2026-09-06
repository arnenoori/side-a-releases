# Side A

Your coding accounts, a track apart.

Side A is a native Mac app shaped like an interactive 3D portable CD player.
Use its physical controls or menu bar companion to choose Claude Code and Codex
accounts, open your project, and continue a saved conversation.

## Download

The first signed, Apple-notarized public build is being prepared. There is no
public installer available yet. Approved downloads will appear under
[Releases](https://github.com/arnenoori/side-a-releases/releases).

## Requirements

- macOS 14 or later, on Apple Silicon or Intel.
- Python 3.9 or later.
- [Claude Code](https://code.claude.com/docs/en/setup) or
  [Codex CLI](https://developers.openai.com/codex/cli), installed separately.
- Your own agent subscription account. Additional accounts are optional.

Side A manages CLI sessions launched through the app. It does not change accounts
in Claude Desktop, the Codex desktop app, or other existing terminals.

## How it works

Open the lid to add accounts and finish the agent's official sign-in. Choose a
project, select an account with the previous/next buttons, then press PLAY. Each
provider keeps its own account pool and conversation history.

Auto flip is optional. It waits for a supported limit event and a safe completed
turn before attempting to resume the same conversation with another opted-in
account. It stops at the agent's prompt so you can review and continue. Codex
integration is experimental and depends on its CLI version. Live multi-account
OAuth and real-limit handoffs are still undergoing acceptance testing.

## Privacy and support

Side A does not collect analytics or send credentials to a Side A service. The
agent CLI owns sign-in and sends requests to its provider under that provider's
policies. Side A stores profile metadata and managed conversation history locally.
Never include credentials, account files, or conversation contents in public
[bug reports](https://github.com/arnenoori/side-a-releases/issues).

This repository contains public release information and binaries only. The app's
source is private. Updates will be available as manual downloads.

Copyright © 2026 Arne Noori. All rights reserved. Side A is independent software,
not affiliated with Sony, Anthropic, or OpenAI.
