# Coeng

Unattended automation, built for the failure cases.

## Public work

| | |
|---|---|
| [gui-report-automation](https://github.com/lon-coeng/gui-report-automation) | Borrows a human-owned Chrome session on a Linux VM to produce a daily report |
| [drive-whisper-transcriber](https://github.com/lon-coeng/drive-whisper-transcriber) | Batch transcription of Google Drive media with Whisper on a Compute Engine VM |

Both are sanitised editions of systems still running in production, published with the client's permission.

## Not public

Most of my work is under contract and cannot be published — around 900 commits, 165 database migrations, a permission system, analytics, and multi-account isolation. The two repositories above are what I can show.

## Stack

**Production** — TypeScript · JavaScript · Python · Node.js · Cloudflare Workers (D1 / KV) · Google Workspace API

**Ops** — systemd · Google Compute Engine · Railway · Playwright · GitHub Actions

## How I work

I design around how things fail — idempotency in state files, quarantine instead of delete, stop when the outcome is unknown, never automate authentication. The two repositories above show what that looks like in practice.

## Availability

Native Japanese speaker, based in Macau (UTC+8) — one hour behind JST, so working hours overlap almost entirely with Japan. Comfortable working in Japanese or English.

日本出身、マカオ在住。日本との時差は1時間で、日本時間での対応が可能です。
