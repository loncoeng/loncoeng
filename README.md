### Coeng

I build small production systems and the automation around them, and design
them around what goes wrong: a request sent twice, a connection that drops
halfway, two people booking the same chair.

TypeScript · Python · Cloudflare Workers · Node.js

### chairside

[chairside](https://github.com/loncoeng/chairside) — bookings, customer records
and takings for a hair salon in Macau: seats that are not interchangeable,
stylists who come and go, and the three currencies a shop there takes.
Cloudflare Workers and D1.

[**Try the demo**](https://chairside.loncoeng.dev) — it runs entirely in your
browser. [DESIGN.md](https://github.com/loncoeng/chairside/blob/main/DESIGN.md)
covers what happens when two people book the same chair at once, or the pay
button is pressed twice.

### Smaller tools

Each one was written for a problem I ran into at work.

*   [flex-guard](https://github.com/loncoeng/flex-guard) — catches the LINE Flex
    messages that fail to send, and the ones that fail quietly.
    [npm](https://www.npmjs.com/package/flex-guard)
*   [publish-guard](https://github.com/loncoeng/publish-guard) — finds what you
    forgot to remove before publishing a repository, git history included.
    [PyPI](https://pypi.org/project/publish-guard/)
*   [durable-webhook](https://github.com/loncoeng/durable-webhook) — a webhook
    relay on Cloudflare Workers that accepts fast and delivers stubbornly.
*   [gui-report-automation](https://github.com/loncoeng/gui-report-automation) —
    drives a Chrome session that a person signed in to, on a Linux VM, to produce
    a daily report.
*   [drive-whisper-transcriber](https://github.com/loncoeng/drive-whisper-transcriber)
    — batch transcription of Google Drive media with Whisper on a Compute Engine VM.

The last two are sanitised versions of systems still running, published with the
client's permission. Most of my work is under contract and cannot be published.
