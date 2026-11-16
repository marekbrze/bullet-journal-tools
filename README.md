<div align="center">

# Notebook tools

**Small tools for keeping a paper notebook.<br>Each one is a single HTML file: it works in the browser, on your phone and offline.**

[**→ Open**](https://marekbrze.github.io/bullet-journal-tools/)

</div>

<br>

| Tool | What it's for |
|---|---|
| [**Start**](start/) | For when you keep putting something off: pick the smallest step, count down from five, work for six minutes. |
| [**Goals**](goals/) | Checklists for your notebook: set up a goal you actually want (picture, one sentence, is it yours, milestones backwards, a 30-day habit, today's step) and check in on it every month. |
| [**Defuse**](defuse/) | A short checklist for a task that has grown too big in your head: say it plainly, “it's just…”, good enough instead of perfect, the straight line worked backwards, the first move now. |
| [**Reset**](reset/) | A short checklist for your notebook when something went wrong: the facts, the thought spiral and the move against it, what you control, one move now. |
| [**Reviews**](reviews/) | Review checklists: morning, evening, week, month, chapter. Tick the steps off one by one. |

No account, no server. Each tool keeps its data in your browser, with export to a file.

## Adding a tool

1. A new folder with `index.html` (one file, no dependencies), plus optional `README.md` and `docs/` with screenshots.
2. The same visual system as the rest: colour tokens on `:root`, dark mode, 640 px width.
3. E-ink mode for Kindle, Kobo, PocketBook, Boox and other e-readers: copy the `e-ink` CSS block, the detection script in `<head>` and the “E-ink mode” footer button from any existing tool. Style new parts for it too: black on white, no grey text, no hover fills or animations, text 16 px or larger, tap targets 44 px or larger. Anything that updates on a timer should touch the page only when what's shown actually changes.
4. Its own `localStorage` key, so tools don't overwrite each other's data.
5. An entry in the table above and a card in the root `index.html` (with the tool's icon, the same one as its favicon).
6. A way back to the tools list: “All tools” top-left on the tool's home screen and in the footer of every view. Links between tools point at `…/index.html` so they also work from disk.
7. Everything in English: interface, content, code comments and docs.
8. Content is written in our own words. No quotes or translations from courses or books.

<br>

<div align="center"><sub>Bullet Journal® is a trademark of Ryder Carroll. This is an independent project, not affiliated with the method's author or bulletjournal.com.</sub></div>
