# Agent Skills

[Agent Skills](https://agentskills.io) are a simple, open format for giving agents new capabilities and expertise.

Skills are folders of instructions, scripts, and resources that agents can discover and use to perform better at specific tasks. Write once, use everywhere.

## Getting Started

- [Documentation](https://agentskills.io) - Guides and tutorials
- [Specification](https://agentskills.io/specification) - Format details
- [Example Skills](https://github.com/anthropics/skills) - See what's possible

This repo contains the specification, documentation, and reference SDK. Also see a list of example skills [here](https://github.com/anthropics/skills).

## About

Agent Skills is an open format maintained by [Anthropic](https://anthropic.com) and open to contributions from the community.

## License

Code in this repository is licensed under [Apache 2.0](LICENSE). Documentation is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). See individual directories for details.

## Netlify Hosting (Mintlify Proxy)

This repository includes `netlify.toml` for hosting the docs via Netlify as a reverse proxy to Mintlify.

1. Edit `netlify.toml` and replace every `https://YOUR_PROJECT.mintlify.app` with your real Mintlify origin.
2. Connect this repo to Netlify and deploy from the repo root.
3. Verify:
   - `/home`
   - `/jp/home`
   - language switcher works between English and Japanese

Note: Mintlify documents reverse proxy support as Enterprise-only. If you are not on Enterprise, use Mintlify native hosting/custom domain instead.
