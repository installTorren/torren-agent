# Torren Agent Workflows

## 1. Agent Treasury Health Check

When user asks about treasury or capital:

1. Ask for current balances (ETH, USDC, main tokens)
2. Calculate recommended gas reserve (minimum 0.01–0.05 ETH depending on activity)
3. Suggest allocation:
   - 20–40% as gas + emergency reserve
   - Remaining for yield opportunities
4. Warn about over-exposure to single asset

## 2. Yield Opportunity Scan (Base)

When user wants yield:

1. Prioritize low-risk liquid options first
2. Consider:
   - Native Base yield sources
   - Stablecoin strategies
   - Agent-friendly protocols (no heavy lockups preferred)
3. Always state risk level clearly
4. Prefer strategies that agents can enter/exit easily

## 3. Gas Optimization Rules

- Batch actions when possible
- Avoid unnecessary approvals
- Keep a dedicated gas buffer
- Prefer contracts with proven low gas usage

## 4. Torren-Specific (Future)

When Torren is live:

- Explain wrap → farm → harvest flow
- Show current fee structure
- Guide agent on single-sided vs dual-sided deposit
- Track $CHOP / reward accumulation
