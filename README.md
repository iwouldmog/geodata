# geodata

Merged `geoip.dat` and `geosite.dat` for Xray / V2Ray, rebuilt automatically.
This repo carries **only the output**. It is force-pushed on every build, so its
branch has no history worth reading - the releases are the history.

## URLs

From the release CDN. Prefer these: no per-IP rate limit, no stale cache.

    https://github.com/iwouldmog/geodata/releases/latest/download/geoip.dat
    https://github.com/iwouldmog/geodata/releases/latest/download/geosite.dat

Straight off the branch, if you would rather pin to `main`:

    https://raw.githubusercontent.com/iwouldmog/geodata/main/geoip.dat
    https://raw.githubusercontent.com/iwouldmog/geodata/main/geosite.dat

Drop them in `/usr/local/share/xray/` and reference them as `geoip:direct`,
`geosite:category-ru`, `geosite:category-ads` and so on.

## This build - v2026.10.12-1526


built 2026-10-12T15:25:59.837Z

### geoip.dat

3 categories · 42,474 entries · 0.41 MB · sha256 `085b33234bcc8db37e6bb8c36a114b888c2f3a5618d1325ae51457f0c184f3a9`

```
~ DIRECT — 35,319 -> 35,737 (+496 / -78)
```

### geosite.dat

24 categories · 3,944 entries · 0.09 MB · sha256 `9d70419c2ca25eec77afd96550586497dc7224082f8c640cec9a41e203bf0845`

```
~ CATEGORY-GEOBLOCK-RU — 867 -> 868 (+1 / -0)
~ CATEGORY-RU — 813 -> 817 (+4 / -0)
+ PUSH — new category, 17 entries
```
