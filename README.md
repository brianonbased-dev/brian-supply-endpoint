# brian-supply-endpoint

API endpoints for `$BRIAN` supply verification on Base.

- Contract: `0x3ecced5b416e58664f04a39dd18935eb71d33b15`
- Symbol: `BRIAN`
- Chain: `Base`

## Machine-readable endpoint

- JSON: https://raw.githubusercontent.com/brianonbased-dev/brian-supply-endpoint/main/supply.json

```json
{
  "symbol": "BRIAN",
  "name": "Brian Arm Strong",
  "chain": "base",
  "contract_address": "0x3ecced5b416e58664f04a39dd18935eb71d33b15",
  "total_supply": "1000000000",
  "circulating_supply": "972025800.487458022074900226",
  "max_supply": "1000000000",
  "updated_at": "2026-04-13T00:00:00Z"
}
```

## Numeric-only endpoints (CMC format)

- Total supply (numeric only): https://raw.githubusercontent.com/brianonbased-dev/brian-supply-endpoint/main/total_supply.txt
- Circulating supply (numeric only): https://raw.githubusercontent.com/brianonbased-dev/brian-supply-endpoint/main/circulating_supply.txt

Values:

- `total_supply`: `1000000000`
- `circulating_supply`: `972025800.487458022074900226`
- `max_supply`: `1000000000`
