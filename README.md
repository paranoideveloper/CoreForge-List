# CoreForge-List

Mirror of the CoreForge subscription **source list** — a directory of subscription URLs
(the same content served at `https://ns1.rmft.tech/list/3b2b89f1ba2d4925213745d8`).

## Files
- **`list.json`** — pretty-printed list of 6 subscription sources.
- **`list.min.json`** — compact single-line JSON (byte-identical to the live endpoint).

## Raw URLs
```
https://raw.githubusercontent.com/paranoideveloper/CoreForge-List/main/list.json
https://raw.githubusercontent.com/paranoideveloper/CoreForge-List/main/list.min.json
```

## Format
```json
{ "items": [ { "id": 1, "kind": "sub", "name": "source-name", "link": "https://..." } ] }
```

Each `link` is itself a subscription URL. Auto-synced from the source of truth.
