# AgentReady Tools

A public catalog of tools that work with AI agents, a read-only [MCP server](https://agentready-tools.com/mcp), and a few of our own Apify Actors. The site is [agentready-tools.com](https://agentready-tools.com). This org holds the [agent skill](https://github.com/agentready-tools/skills) and some [guides](https://github.com/agentready-tools/guides).

## Where to find us

- Website: [agentready-tools.com](https://agentready-tools.com)
- Catalog: [tools.json](https://agentready-tools.com/tools.json) · [llms.txt](https://agentready-tools.com/llms.txt)
- Public MCP server: [https://agentready-tools.com/mcp](https://agentready-tools.com/mcp) ([docs](https://agentready-tools.com/docs/mcp))
- Official MCP Registry: [`com.agentready-tools/catalog`](https://registry.modelcontextprotocol.io/?q=com.agentready-tools/catalog)
- Glama: [AgentReady Tools connector](https://glama.ai/mcp/connectors/com.agentready-tools/catalog)
  [![Glama score](https://glama.ai/mcp/connectors/com.agentready-tools/catalog/badges/score.svg)](https://glama.ai/mcp/connectors/com.agentready-tools/catalog)
- Apify Store: [`samgov-tools`](https://apify.com/samgov-tools) (Actors listed below)
- GitHub: [agentready-tools](https://github.com/agentready-tools) · [agentready-tools/skills](https://github.com/agentready-tools/skills)
- X: [@AgentReadyTools](https://x.com/AgentReadyTools)
- Reddit: [u/AgentReadyTools](https://www.reddit.com/user/AgentReadyTools)
- dev.to: [agentreadytools](https://dev.to/agentreadytools)
- Substack: [agentreadytools.substack.com](https://agentreadytools.substack.com)
- Examples: [agentready-tools/skills/examples](https://github.com/agentready-tools/skills/tree/main/examples)

In Claude Code, add the plugin marketplace and install the skill:

```text
/plugin marketplace add agentready-tools/skills
/plugin install agentready-tools@agentready-tools
```

### Not listed yet

<!-- UPDATE-WHEN-LIVE: claude-directory
     Replace the line below with a markdown link to the official Anthropic / Claude plugin directory listing once it is public. Do not link a guessed URL. -->
- Claude plugin directory: under review. We'll add the official listing link here once it's public.

<!-- UPDATE-WHEN-LIVE: chatgpt-directory
     Replace the line below with a markdown link to the official ChatGPT / OpenAI apps or plugin directory listing once it is submitted and approved. Do not link a guessed URL. -->
- ChatGPT apps / plugin directory: not submitted yet (waiting on identity verification). The listing link goes here when it exists.

<!-- UPDATE-WHEN-LIVE: awesome-claude-skills
     If https://github.com/karanb192/awesome-claude-skills/pull/723 is merged, replace this with a link to the merged list entry. -->
- [awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills/pull/723): pull request is open, not in the list yet.

## Actors

These are live on Apify, under the [`samgov-tools`](https://apify.com/samgov-tools) account:

- [SAM.gov Contract Opportunities](https://apify.com/samgov-tools/samgov-opportunities). Federal RFPs, solicitations, and related notices, as JSON or a spreadsheet. The official daily extract does not need a SAM.gov API key.
- [Website Screenshot](https://apify.com/samgov-tools/url-screenshot). PNG, JPEG, or PDF captures of public URLs.
- [ATS Jobs](https://apify.com/samgov-tools/ats-jobs). Current Greenhouse and Lever postings, from those boards' public APIs.
- [USAspending Awards](https://apify.com/samgov-tools/usaspending-awards). Federal contract awards, IDVs, and grants.
- [Agent Payment Checker](https://apify.com/samgov-tools/agentpay-checker). Reports whether a URL advertises x402, MPP, L402, UCP, or AP2.
- [Agent Wallet Spend Report](https://apify.com/samgov-tools/agent-spend). Totals and top payees for x402 and MPP wallet spend, from public chain data. Read-only.

## Guides

- [Pull SAM.gov contract opportunities into a spreadsheet](https://github.com/agentready-tools/guides/blob/main/samgov-opportunities-to-spreadsheet.md)
- [Screenshot a list of URLs from an AI agent](https://github.com/agentready-tools/guides/blob/main/screenshot-urls-via-apify-api.md)
