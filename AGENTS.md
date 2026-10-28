# Notes for agents

- Static single-file site (`index.html`, Tailwind via CDN). Served by nginx in `docker-compose.base44.yml` with the repo bind-mounted read-only; edits show on page reload (no build step, no HMR).
- The "LLM tutor" section calls the Gemini API directly from the browser with `apiKey = ""` hardcoded (index.html ~line 460). It won't work without a key, and any key placed there is public to visitors — a real fix needs a small backend proxy.
