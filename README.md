# live-call

A live voice "team meeting" for planning the New Rayyan Trading website: you plus 11 Claude specialists in a Meet-style call.

`index.html` is a single static page, served with GitHub Pages from `main`.

- Replies come from the Claude API, called from your browser with your own Anthropic API key. Paste the key in the call record drawer; it is saved only in that browser. Never commit a key to this repo.
- Voices and the mic use the browser's built-in speech features (best in Chrome or Edge). Where they are missing, the page falls back to captions and typing.
- Research uses Claude's web search tool.
