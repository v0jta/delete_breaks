**Line Break Remover — paste → no breaks**

Tiny React utility that flattens any line breaks (`\r\n`, `\n`, `\r`) into single spaces and trims edges.  
Optimised for messy copy-pastes from PDFs, emails, OCR, or exports where random breaks sneak in.

- Auto-flattens as you paste/type.
- Auto-copies the cleaned text to your clipboard; falls back gracefully if clipboard is blocked (shows ⌘C/Ctrl+C hint or a “Copy now” button).
- Keeps tabs as-is (configurable later), handles Windows/Unix/old-Mac endings.
- Includes lightweight in-app tests.

**Use it:** Open the page, paste your text into the box — it’s immediately flattened and copied for you.
