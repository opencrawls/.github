<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./wordmark-dark.svg">
  <img alt="OpenCrawls" src="./wordmark-light.svg" width="460">
</picture>

**Open intelligence for web scraping, crawling and data acquisition.**<br>
Tools, proxy providers, target websites and the companies behind them, with evidence for every claim.

[Website](https://opencrawls.com) · [Targets](https://opencrawls.com/targets) · [Proxies](https://opencrawls.com/proxies/providers) · [Directory](https://opencrawls.com/directory) · [API](https://opencrawls.com/api/v1/openapi.json) · [Contact](mailto:contact@opencrawls.com)

</div>

---

### What we build

| Project | What it does |
|---|---|
| **[Scrapalyzer](https://github.com/opencrawls/scrapalyzer)** | Open-source Python library that profiles a website before you scrape it: internal APIs, anti-bot vendor, rendering mode, login walls, structured data, pagination. Every answer comes with its evidence. It is the engine behind OpenCrawls Targets. |
| **[Target Intelligence](https://opencrawls.com/targets)** | A technical profile of each popular data source: rendering, documented APIs, pagination, structured data, infrastructure and bot protection, from dated checks. |
| **[Proxy directory](https://opencrawls.com/proxies/providers)** | Proxy providers by type, protocol, authentication and pricing model, with side-by-side [comparisons](https://opencrawls.com/proxies/compare). |
| **[Directory](https://opencrawls.com/directory)** | Open-source scraping and crawling tools and the companies in the space: proxy networks, scraping APIs, browser infrastructure, bot defense. |

### Public API

Read-only, no key required. Described in [OpenAPI 3.1](https://opencrawls.com/api/v1/openapi.json).

```bash
# targets with a documented API, protected by Akamai
curl "https://opencrawls.com/api/v1/targets?api=true&waf=akamai"

# one target's technical profile
curl "https://opencrawls.com/api/v1/targets/walmart"
```

`/targets` · `/targets/{slug}` · `/targets/{slug}/apis` · `/pagination` · `/data-inventory` · `/observations` · `/industries` · `/statistics`

### Get involved

- Try **[Scrapalyzer](https://github.com/opencrawls/scrapalyzer)** on a site you scrape and open an issue when it gets something wrong.
- Spotted a wrong value on [opencrawls.com](https://opencrawls.com)? Email **[contact@opencrawls.com](mailto:contact@opencrawls.com)** with a source.
- Data, corrections and partnership requests go to the same address.
