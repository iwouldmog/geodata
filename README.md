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

## This build - v2026.08.29-0935


built 2026-08-29T09:35:44.541Z

### geoip.dat

3 categories · 42,394 entries · 0.41 MB · sha256 `c5ad35fef96329caaf8387de2934dccb133c2c4481a1c2a9a8c6bc82b6c6a2e0`

```
no change
```

### geosite.dat

23 categories · 3,921 entries · 0.09 MB · sha256 `7ebf2f9184af858e760787495df664418512336a2e6e3dbd615119ba0eade982`

```
~ CATEGORY-GEOBLOCK-RU — 880 -> 867 (+0 / -13)
```
