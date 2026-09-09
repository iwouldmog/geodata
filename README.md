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

## This build - v2026.09.09-1123


built 2026-09-09T11:23:42.061Z

### geoip.dat

3 categories · 42,616 entries · 0.41 MB · sha256 `b285f198caf47b2e54cac03bb612ff07f49ef94c7ebb5008002c6503581a4092`

```
~ DIRECT — 35,892 -> 35,879 (+12 / -25)
```

### geosite.dat

23 categories · 3,921 entries · 0.09 MB · sha256 `7ebf2f9184af858e760787495df664418512336a2e6e3dbd615119ba0eade982`

```
no change
```
