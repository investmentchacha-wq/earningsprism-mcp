# EarningsPrism MCP Server

Real-time AI-summarised SEC filing intelligence for Claude, Cursor, and any MCP-compatible AI client.

## Tools

| Tool | Description |
|---|---|
| `get_filings_8k` | SEC 8-K filings for US stocks — earnings, M&A, leadership, financial events |
| `get_filings_6k` | SEC 6-K filings from 600+ Foreign Private Issuers (FPI) |
| `get_insider_trades` | SEC Form 4 insider buys and sells |
| `get_filing_analytics` | Filing volume breakdown by category, sector, signals |
| `search_company` | Company lookup by ticker or name |

## Server URL
https://www.earningsprism.com/mcp

## Authentication

Pass your EarningsPrism API key as `X-API-Key` header.  
Get a key at [earningsprism.com](https://www.earningsprism.com) with Standard or Premium plan.

## Coverage

- 11,000+ US stocks across S&P 500, NASDAQ 100, DOW 30, Russell 1000/3000
- 600+ Foreign Private Issuers (FPI) — ASML, Toyota, Shell, Samsung, SAP, Ericsson
- 11 international markets — UK, Japan, Korea, France, Spain, Sweden, Poland, Brazil, Chile, Argentina, Tunisia

## Links

- [Live server](https://www.earningsprism.com/mcp)
- [Documentation](https://www.earningsprism.com/newsroom)
- [Smithery listing](https://smithery.ai/server/investmentchacha/earningsprism)
