# MM-JDD

MAME4droid 0.139u1 ROM set - repository layout, manifest and documentation.

## Status

This repository currently contains **documentation and the manifest only**.

- ROM archives (`*.zip`) and cover images are **not published**.
- Redistribution rights have **not been established** for any of the 104 ROMs.
- The full list that must be cleared first is in
  [`docs/AUTHORIZATION_NEEDED.md`](docs/AUTHORIZATION_NEEDED.md).

| Item | Count |
|---|---|
| ROMs in manifest | 104 |
| Matching covers in manifest | 104 |
| ROM bytes (local, not uploaded) | 689.02 MB |
| Cover bytes (local, not uploaded) | 8.51 MB |

## Layout

```
games/<ROM_NAME>/<ROM_NAME>.zip
games/<ROM_NAME>/cover.jpg
```

Every ROM directory already exists. Add files only after their
redistribution rights are established.

## Files

- `MANIFEST.csv` - 104 ROMs with paths, byte sizes, SHA-256 and matching cover
- `games/README.md` - folder rules
- `docs/AUTHORIZATION_NEEDED.md` - files awaiting redistribution authorization

## Adding an authorized ROM

1. Confirm redistribution permission (license, rights-holder statement, or
   documented public-domain / freeware status).
2. Copy `ROM_NAME.zip` and `cover.jpg` into `games/ROM_NAME/`.
3. `git add -f games/ROM_NAME/ROM_NAME.zip games/ROM_NAME/cover.jpg`
4. Commit and push to `main` (never force push).

Binaries are git-ignored by default to prevent an accidental upload.
