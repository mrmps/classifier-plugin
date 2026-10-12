# classifier.dev

Classify batches of text into your own labels, tag multiple topics, count categories and review uncertain results. Includes hosted classification and documentation MCP servers and the bulk-classify skill. Public calls need no API key.

## Install

Gemini CLI:

```sh
gemini extensions install https://github.com/mrmps/classifier-plugin
```

Cursor and other Agent Plugins 1.0 clients can install this repository as a plugin. For a local Cursor install, clone it to `~/.cursor/plugins/local/classifier` and reload Cursor. Review any existing folder before replacing it. Public marketplace availability depends on review.

For Claude Code, Codex, Muse Code and Grok Build, use the [platform-specific instructions](https://github.com/mrmps/classifier-dev/tree/main/plugins/classifier).

## Data handling

Synchronous classification text, labels, instructions and results are retained for training and operator review by default. Set `share_data: false` to opt out. The bundled skill directs agents to opt out unless the user chooses to contribute. Confidence can be null. Public requests are subject to service limits; workspace usage needs a workspace key configured separately.

[Website](https://classifier.dev) · [Privacy](https://classifier.dev/privacy) · [Terms](https://classifier.dev/terms) · [Support](https://classifier.dev/contact)

## Source

This is the public distribution snapshot for version 1.1.0, generated from [classifier-dev commit a7bad5f](https://github.com/mrmps/classifier-dev/commit/a7bad5f42df87c0bd8ec1995351e82f07af94488) using `npm run package:plugins`. Copy the portable bundle, then the Gemini manifest, to refresh it; preserve this README and the MIT license. Runtime implementation and development belong in that source repository.
