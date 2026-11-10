# Privacy

HotKey does not collect or send any personal data about you.

- **No accounts, no analytics, no tracking, no advertising.**
- **What you type stays on your PC.** HotKey watches the keyboard only to fix the current word. Typed text is never written to disk and never leaves the computer. Password fields are always skipped.
- **Voice, grammar and translation run locally.** Whisper, Qwen and Opus-MT run on your graphics card or processor. Not a single word of your speech or text is uploaded.
- **Dictation history** is kept on your PC, encrypted with your Windows account (DPAPI), and is deleted automatically after 1, 3 or 7 days. You can clear it at any time or switch it off.

## When HotKey goes online

Only in three cases, and never with your text:

| What | When | Where |
|---|---|---|
| Model download | Only when you press **Download** | Hugging Face. Every file is checked by size or SHA-256 |
| Update check | Once a day, if **Update automatically** is on (default) | GitHub Releases of this repository. No account, no token, only the version number is compared |
| Feedback | Only when you press **Open on GitHub** in *Complaints and suggestions* | Your browser opens a pre-filled issue form here. Nothing is sent until you press *Submit* yourself. You see everything that will be sent before that |

Settings live in `%AppData%\HotKey\`, models and logs in `%LocalAppData%\HotKey\`. Logs contain only events like "convert len=6 ru", never the words themselves.

Questions about privacy: open an [issue](../../issues).
