# ShopOracle — E-Commerce Intelligence MCP Server

> Product search, price comparison, competitor analysis, stock monitoring, reviews across Amazon, eBay, Google Shopping. 11 tools, 18 countries.

**Part of [ToolOracle](https://tooloracle.io) — Policy-enforced, tier-gated, usage-metered tool execution**

## Connect

```bash
npx -y mcp-remote https://tooloracle.io/shop/mcp/
```

## x402 Pay-per-call (autonomous agents)

```
POST https://tooloracle.io/x402/shop/mcp/
→ 402 with structured pricing → Send USDC on Base → Retry with X-PAYMENT header
```

## 11 Tools · 1 unit = $0.01

| Tool | Units | Price | Tier |
|------|-------|-------|------|
| `competitor_pricing` | 10 | $0.10 | Premium |
| `compare_prices` | 8 | $0.08 | Deep |
| `product_search` | 5 | $0.05 | Deep |
| `bestseller_list` | 5 | $0.05 | Deep |
| `market_position` | 5 | $0.05 | Deep |
| `review_summary` | 5 | $0.05 | Deep |
| `track_price` | 3 | $0.03 | Standard |
| `stock_monitor` | 3 | $0.03 | Standard |
| `price_history` | 2 | $0.02 | Standard |
| `price_alert` | 2 | $0.02 | Standard |
| `health_check` | 0 | free | — |

## Tier gating

| Tier | Max/call | Blocked |
|------|----------|---------|
| Free ($0) | 3 units | competitor_pricing |
| Starter ($49/mo) | 8 units | — |
| Pro+ / x402 | 15 units | — |

## 18 Countries

DE, US, UK, FR, ES, IT, NL, AT, CH, SE, NO, DK, PL, BR, CA, AU, JP, IN

## Links

- [ToolOracle](https://tooloracle.io) · [x402 Gateway](https://tooloracle.io/x402/)
- [RankOracle](https://github.com/ToolOracle/rankoracle) · [MemeOracle](https://github.com/ToolOracle/memeoracle) · [YieldOracle](https://github.com/ToolOracle/yieldoracle) · [SmartMoneyOracle](https://github.com/ToolOracle/smartmoneyoracle)
