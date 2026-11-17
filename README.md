# live-call

A live voice "team meeting" for planning the New Rayyan Trading website: you plus 11 Claude specialists in a Meet-style call.

`index.html` is a single static page, served with GitHub Pages from `main`.

- Replies come from the model provider you pick in the call record drawer: Groq, OpenRouter or Google Gemini (free keys), a slow no-key option, Kimi, any OpenAI-compatible service, or Claude. Keys are saved only in your browser. Never commit a key to this repo.
- Voices and the mic use the browser's built-in speech features (best in Chrome or Edge). Where they are missing, the page falls back to captions and typing.
- Research can search the web only when Claude powers the team.
