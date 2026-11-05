# CrakSEO SEO MCP extension for Gemini CLI

SEO tools for Gemini CLI: keyword research, live Google SERPs, rank tracking,
backlinks and site audits, plus a free Google Search Console MCP with Bing
Webmaster Tools and free URL submission to IndexNow and Bing.

It connects three hosted [CrakSEO](https://crakseo.com/mcp) MCP servers:

| Server | What it does | Price |
| --- | --- | --- |
| `crakseo-seo` | Keyword search volume, difficulty and CPC, keyword ideas, Google and Bing SERPs with AI Overview sources, rank checks, competitor keywords, backlinks and referring domains, site audits with Core Web Vitals, Google Maps rankings, ChatGPT and Perplexity brand mentions | Pay per call from prepaid credits; the price is shown before each call |
| `crakseo-search-console` | Your own Google Search Console and Bing Webmaster Tools data: queries, clicks, impressions, CTR, position, URL inspection, sitemaps | Free |
| `crakseo-url-indexing` | Free IndexNow, Bing and sitemap submission and index checks, plus optional paid force indexing with a quote you approve | Free, paid option |

## Install

```bash
gemini extensions install https://github.com/CrakSEO/gemini-cli-extension
```

Then sign in to each server you want to use:

```text
/mcp auth crakseo-seo
/mcp auth crakseo-search-console
/mcp auth crakseo-url-indexing
```

## Try it

- "What are the search volume and keyword difficulty for 'seo mcp server' in the US?"
- "Which queries brought clicks to my site in Search Console last week?"
- "Who ranks in the top 10 on Google for 'serp api', and what backlinks do they have?"
- "Submit my new blog post to IndexNow and check whether Google has indexed it."

## Links

- Docs: https://docs.crakseo.com
- Other clients (Claude, Cursor, ChatGPT, VS Code, Codex): https://crakseo.com/mcp
- Plugins for Claude Code and Cursor: https://github.com/CrakSEO/crakseo-mcp-plugins

MIT licensed.
