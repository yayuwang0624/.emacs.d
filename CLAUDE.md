# CLAUDE.md

## Code style

Write self-documenting code. Rationale, tradeoffs, and caveats go in the chat
response, where I can read and reply to them.

Files carry no commentary: no `;;` lines, no trailing comments, no prose between
`config.org` blocks.

Docstrings are not commentary. Keep them on `defun`, `defvar`, `defcustom`.
