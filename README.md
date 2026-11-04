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

## This build - v2026.11.04-0036


built 2026-11-04T00:36:10.070Z with geodata-studio `184e360`

### geoip.dat

5 categories · 107,080 entries · 1.28 MB · sha256 `3de0980ae6d51e63639d64d744d749ff963a4d76f235934fa93c5d1dee0bf9fb`

```
+ DIRECT-NEW — new category, 63,908 entries
```

### geosite.dat

24 categories · 3,947 entries · 0.09 MB · sha256 `201c0c3c681a6484e427d4ae48e43e7ecbf883bb581f02c5a7231eb90e8ca866`

```
~ GOOGLE-DEEPMIND — 41 -> 43 (+2 / -0)
```
