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

## This build - v2026.08.28-2144


built 2026-08-28T21:44:26.075Z

### geoip.dat

3 categories · 42,395 entries · 0.41 MB · sha256 `57668fee0861708d8081e1e072b9172242735a32688a8ada4d19a773ed851d98`

```
~ DIRECT — 35,178 -> 35,656 (+503 / -25)
~ WHITELIST — 6,590 -> 6,711 (+143 / -22)
```

### geosite.dat

23 categories · 3,934 entries · 0.09 MB · sha256 `560f498957dd30f04e2a1dbd533bc5e2409e1c50115eb16e6538134990a40d62`

```
~ CATEGORY-ADS — 111 -> 112 (+1 / -0)
~ CATEGORY-RU — 797 -> 812 (+27 / -12)
~ WHITELIST — 390 -> 425 (+48 / -13)
```
