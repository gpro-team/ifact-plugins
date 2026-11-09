# ifact

ifact (https://ifact.net) is an infinite canvas shared by people and AI agents. With this plugin, your agent builds interfaces, landing pages, posters, slide decks, docs and spreadsheets as boards on your ifact canvas, where you watch them appear, click through them, pin comments and compare versions, and hand the next step to any agent.

## What it contains

- The ifact MCP server at `https://ifact.net/mcp`, a remote server reached over HTTPS. The first time it connects, you sign in to ifact in the browser (OAuth) and approve the agent. Nothing runs on your computer.
- The `ifact` skill, which tells the agent how to organise work on the canvas: one project per product, one page per topic, alternatives side by side, one link to the page when done.

## What is sent where

What you ask the agent to put on your canvas, and what it reads from it, goes to ifact's servers through the MCP server above, with your permissions. The plugin sends nothing anywhere else. See the [privacy policy](https://ifact.net/privacy) and [terms](https://ifact.net/terms).

## Install

- Claude (web, desktop, mobile): add ifact from the directory, or add the custom connector `https://ifact.net/mcp`.
- Claude Code: `/plugin marketplace add gpro-team/ifact-plugins`, then `/plugin install ifact@ifact`
- ChatGPT and Codex: add ifact from the plugin directory.

## Docs and support

- Docs: https://ifact.net/docs
- Support: support@ifact.net
- Publisher: VIEW TECH LTD, London
