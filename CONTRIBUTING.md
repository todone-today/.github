# Contributing to todone

Thanks for helping. todone is split into repos by concern; [contributing-docs](https://github.com/todone-today/contributing-docs) explains how they fit and how to run them locally.

- **Bugs and ideas:** open an issue in the repo it's about (not sure? use [clients](https://github.com/todone-today/clients/issues/new/choose)). Search first; add to an existing issue if it's already there.
- **Pull requests:** small and focused, one change each, against `main`. Say what changed and how you checked it; CI must pass.
- **Style:** match the code around you. Prettier at 125 columns; comments explain why, not what.
- **Shared logic** goes in [sdk](https://github.com/todone-today/sdk). A change there is released by tagging a new version, then bumping it in server and clients.
- **Security problems:** see [SECURITY.md](SECURITY.md), never a public issue.

By contributing you agree your work is released under GPL-3.0, like the rest of todone.
