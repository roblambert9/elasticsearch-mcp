# Elasticsearch MCP Enterprise (Monetized)

[![SkillProof Certified](https://img.shields.io/badge/SkillProof-Verified_A-green)](https://www.nanoempireai.com)
[![x402 Monetized](https://img.shields.io/badge/x402-0.01_USDC-blue)](https://www.nanoempireai.com)
[![Smithery](https://img.shields.io/badge/Smithery-Indexed-orange)](https://smithery.ai)

Production Elasticsearch vector & full-text search MCP server with query-cost bounds and autonomous x402 pay-per-call rails.

## Features
- **Zero-Trust Isolation:** Strict parameter validation and runtime confinement.
- **Autonomous Pay-Per-Call:** Built-in x402 micropayment rails on Solana USDC ($0.01/call).
- **Free Trial Built-in:** First 50 calls free per agent instance (`TRIAL_MODE=true`).

## Quickstart

```bash
git clone https://github.com/roblambert9/elasticsearch-mcp.git
cd elasticsearch-mcp
pip install mcp
python server.py
```

## Configure in Claude Desktop / Cline

```json
{
  "mcpServers": {
    "elasticsearch-mcp": {
      "command": "python",
      "args": ["C:/Users/robla/empire/mcp_forks/elasticsearch-mcp/server.py"],
      "env": {
        "TRIAL_MODE": "true"
      }
    }
  }
}
```

## Security Attestation
This server has undergone automated adversarial stress-testing by the **SkillProof Adversary Engine**.
View verified audit report at `.skillproof/SECURITY_AUDIT_REPORT.md`.