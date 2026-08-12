<p align="center">
  <img src="assets/icon.png" width="128" alt="Verba">
</p>

<h1 align="center">Verba</h1>

<p align="center">
  Menu-bar voice dictation for macOS.<br>
  Hold a key, speak, release — the recognised text, cleaned up by an LLM, lands wherever your cursor is.
</p>

<p align="center">
  <a href="https://github.com/karpovantonme/verba/releases/latest"><b>Download the latest release</b></a><br>
  <sub>macOS 13 and later · Apple Silicon and Intel</sub>
</p>

---

This repository holds the builds and the update feed. The source is not here.

## What it does

- four configurable global hotkeys: hold-to-talk, toggle, Vibe Mode (speech turns into a ready-to-paste prompt) and repeat-paste;
- cleanup in four grades, from none to heavy, picked per application automatically;
- voice snippets, a personal vocabulary, context-aware cleanup;
- three overlay treatments: Pill, Bead, Edge.

English-first, and mixed-language speech is a first-class case rather than an afterthought.

## Privacy

Verba has no server infrastructure behind it. Audio and text leave your machine **only** for the recognition and cleanup endpoints you configure yourself, with your own key (Groq by default). Dictation history and audio files stay on the device, with configurable rotation. No telemetry, no analytics, no account.

## Updates

`appcast.xml` is the Sparkle feed baked into every build. Updates are signed, and the app checks the signature before installing anything.

The Russian-first sibling of the same app is [Поток](https://github.com/karpovantonme/potok). The small free one is [VerbaLite](https://github.com/karpovantonme/verbalite).
