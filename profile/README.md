# FinBot-Crypto

Robô de trading algorítmico 24/7 na Binance (Oracle Cloud VPS).

## Repositórios ativos

| Repo | Descrição |
|------|-----------|
| **[finbot-v2](https://github.com/FinBot-Crypto/finbot-v2)** | Monorepo de produção — core + Leme + ML |
| **[fb-infra](https://github.com/FinBot-Crypto/fb-infra)** | PostgreSQL 16 + NATS JetStream |

## Repositórios arquivados

Substituídos pelo monorepo `finbot-v2`: `fb-market-selection`, `fb-strategy-ml`, `fb-decision-engine`, `fb-trade-decision`, `fb-execution`, `fb-execution-futures`, `fb-position-management`, `fb-analytics`, `fb-web-dashboard`, `fb-ml-training`, `fb-ml-validation`

## Deploy

Push em `finbot-v2` main → runner VPS → `/root/crypto-bot`
