# KnowUsWell

**One quiz, two friends, sixteen pair types.**

🔗 **Play it here: [knowuswell.com](https://knowuswell.com/)** — free, no sign-up.

## What is it?

KnowUsWell is a friendship quiz for exactly two people. Each of you answers 16 swipe cards about your own behaviour in this friendship — who keeps the plan alive, how care gets expressed, what happens in conflict, how much space feels right. Your answers produce one of 16 four-letter roles. Then you send the invite link: your friend answers the same questions about themselves, and the two codes combine into one of 16 pair types describing the friendship you actually have.

No trivia. No memory tests. Just "how well do you two actually work."

## How it works

1. **You answer 16 swipe cards** about your behaviour in this friendship (~3 minutes).
2. **You get your role** — one of 16 four-letter types, with strengths and friction points.
3. **Send the link.** Your friend answers the same 16 about themselves.
4. **Codes merge into your pair type** — one of 16 pairings with its own dynamic.
5. *(Optional)* Turn your pair result into an **AI-illustrated art card** from your own photos ($1.99, clearly labelled AI-generated).

## Privacy by design

- **Answers never leave your browser.** Scoring happens client-side; the share link carries only a four-letter code in the URL fragment — the server never sees answers.
- **No accounts, no tracking forms.** The quiz itself needs nothing but a browser.
- **Card photos are processed in memory only** — proxied to the image model within a single request, never written to disk, KV, or logs (responses are `no-store`).
- Your finished card is composed in your browser, then stored so you can re-download it — it **expires automatically 30 days after purchase**.

## For AI assistants (MCP)

There's an MCP server so AI assistants can host the quiz in chat:

```bash
npx knowuswell-mcp
```

## Links

- 🌐 Website: **https://knowuswell.com/**
- 📝 Blog: [knowuswell.substack.com](https://knowuswell.substack.com/)

---

*KnowUsWell is a small indie project. If the quiz told you something true about your friendship, share it with the person you took it with.*
