# Changelog

## 1.3.19 - 2025-12-30
- Show first user message in the preview pane (fallback to first message).

## 1.3.18 - 2025-12-30
- Use last assistant message as the default preview snippet when not searching.
- Add an `about` field (last assistant message fallback) to JSON output.

## 1.3.17 - 2025-12-30
- Add session/window listing support to tmux-cli in local mode.
- Allow list_panes to target a specific session/window.

## 1.3.16 - 2025-12-30
- Skip Codex git repo checks for query to avoid trusted-dir failures.

## 1.3.15 - 2025-12-30
- Make query use a sanitized transcript (first user + last 100 assistant messages).
- Use Codex 5.1 mini for codex sessions in CLI query.

## 1.3.14 - 2025-12-30
- Add cached/noncached token totals and cached share to JSON output.
- Show cached/noncached breakdown in the TUI preview pane.

## 1.3.13 - 2025-12-30
- Show total tokens in the TUI preview pane.

## 1.3.12 - 2025-12-30
- Skip environment context blocks when deriving user previews.

## 1.3.11 - 2025-12-30
- Skip the AGENTS.md preload when deriving `first_user_msg`/`last_user_msg`.
- Fix total token extraction when token_count info is null.

## 1.3.10 - 2025-12-30
- Add `last_user_msg` and `last_assistant_msg` to `aichat search --json`.
- Capture first/last user and last assistant previews with role-specific lengths.

## 1.3.9 - 2025-12-30
- Add `first_user_msg` and `total_tokens` to `aichat search --json` output.
- Index the first user message content and total token count from session JSONL.
- Include `first_user_msg` and `total_tokens` in YAML exports for indexing.
