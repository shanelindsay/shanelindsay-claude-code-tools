# Changelog

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
