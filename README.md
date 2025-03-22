## E2B x Eliza

__Problem__: Agents using the most used AI Agent framework cannot leverage E2B to run the code the agent generates in a sandbox.

__Solution__: We wrote [`plugin-sandbox`](https://github.com/Vojtch159/plugin-sandbox) for the Eliza AI Agent framework that any agent using this framework can easily use.

This is a demo repository where we included the plugin as a submodule. The demo is a showcase of a simple AI Agent using the plugin to interface with E2B.

## Demo GIF

![Demo GIF](demo.gif)

## Links

- Demo repo: https://github.com/Vojtch159/eliza-e2b
- Plugin repo: https://github.com/Vojtch159/plugin-sandbox
- Eliza docs: https://eliza.how/

## How to run the demo locally

Make sure you have `OPENAI_API_KEY` and `E2B_API_KEY` environment varibles set.

1. `pnpm i`
2. `pnpm build`
3. Start
3.1. `pnpm start`
3.2. `pnpm start:client` in second terminal