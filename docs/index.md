# Side A

A vintage 3D player for your Claude Code and Codex accounts. A standalone Mac app and menu bar companion, made by [Arne Noori](https://arne.ai).

## Download

The signed and Apple-notarized public preview is available. Download the universal DMG from [official releases](https://github.com/arnenoori/side-a-releases/releases). Only published stable releases containing a universal macOS DMG and SHA256SUMS.txt appear as downloads on the website. The interactive player on this website uses demo accounts.

## Setup

1. Download the signed DMG. Drag Side A to Applications.
2. Open the player's lid. Setup checks Python and your agent CLI. Add an account, complete the provider's official sign-in, then return to Side A.
3. Choose a project. Press play.

## Requirements

- macOS 14 or later, Apple Silicon or Intel.
- [Python 3.9 or later](https://www.python.org/downloads/macos/).
- [Claude Code](https://code.claude.com/docs/en/setup) or [Codex CLI](https://developers.openai.com/codex/cli).
- An account with Claude Code or Codex access enabled.

## Account switching

Side A keeps separate account profiles for Claude Code and Codex. Use the player's previous and next controls to select an account. The app can run as the 3D player or from the menu bar.

Switching applies to sessions started in Side A. Codex integration and Auto flip are experimental; real multiple-account handoffs are still being validated. Side A does not increase provider limits or guarantee uninterrupted sessions.

## Troubleshooting

If a switch is waiting, return to Terminal to finish the turn or submit or clear your draft. Side A never replays a prompt for you. Settings and Help offer a local diagnostic summary with app/tool versions and session state. No accounts, paths, conversations, or credentials are included, and nothing is uploaded.

## Privacy

Your profiles stay on your Mac. Claude and Codex handle sign-in and requests under their own policies. App versions before 0.4 have no analytics. Starting with 0.4, anonymous app statistics are off by default: opt in during setup or in Settings to share setup, session, and handoff counts. App statistics use a new anonymous ID each launch and include no accounts, emails, code, or project paths. Turn them off at any time in Settings. The website sends anonymous page views, download clicks, and demo interactions to PostHog in the US, with no cookies, recordings, or persistent visitor IDs. Reloading starts a new anonymous visit. No account data, URL queries, or conversation content is sent. Turn website statistics off in Setup → Requirements → Privacy; Do Not Track and Global Privacy Control are also respected. This preference is stored locally. The page checks GitHub for public downloads. Side A is an independent app, not affiliated with Anthropic, OpenAI, or Sony.

## Machine-readable resources

- [Product information](https://getsidea.com/product.json)
- [API description](https://getsidea.com/openapi.json)
- [Setup skill index](https://getsidea.com/.well-known/agent-skills/index.json)
- [Resource catalog](https://getsidea.com/.well-known/ard.json)

The public website and product information do not require authentication. No public account-management, OAuth, MCP server, or payment endpoint is provided. Browsers that support WebMCP can read product information and check official download availability.
