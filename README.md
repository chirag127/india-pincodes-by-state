# PIN Codes Grouped by State

> PIN codes grouped by state with counts

**Category:** india-geo · **Data:** India Post open data · **License:** CC-BY-4.0 · **Updates:** monthly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/pincodes-by-state.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/india-pincodes-by-state/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/india-pincodes-by-state/data.json');
const data = await res.json();
```

## Data

- Source: India Post open data
- License: CC-BY-4.0
- Last updated: `2026-08-25T03:49:45.775Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/india-pincodes-by-state/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC-BY-4.0
