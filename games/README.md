# games/

One directory per ROM set, already created for all 104 entries in
`MANIFEST.csv`:

```
games/<ROM_NAME>/<ROM_NAME>.zip
games/<ROM_NAME>/cover.jpg
```

Rules:

- Do **not** extract or modify ROM ZIPs.
- Only add a ZIP or cover after its redistribution rights are established.
- `.gitignore` excludes `*.zip` and image files here; after clearance add the
  files explicitly with `git add -f ...`.
- Each directory may keep a `.gitkeep` placeholder so the structure is tracked.
