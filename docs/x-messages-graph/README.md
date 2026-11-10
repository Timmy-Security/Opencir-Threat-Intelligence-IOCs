# X messages graph

Offline visualizations for `lab.lab.x_messages` (embedded snapshot). Serve this folder over HTTP — do not rely on `file://` for hash routing.

| Entry | Path | Notes |
|-------|------|-------|
| **Mindmap (default)** | [`x_messages_mindmap.html#/global`](x_messages_mindmap.html#/global) | Full HUD, filters, replay animation, hash routes (`#/global`, `#/agents`, …) |
| Force graph | [`x_messages_graph.html`](x_messages_graph.html) | Hub uses `assets/cir-logo.png` (**CIR AI power** crawl engine) |
| Folder default | [`index.html`](index.html) | Redirects to mindmap global view |

GitHub Pages (when `docs/` is the site root): `…/x-messages-graph/` or `…/x-messages-graph/index.html` → mindmap `#/global`.
