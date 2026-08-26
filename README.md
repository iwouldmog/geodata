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

## This build - v2026.08.26-0709


built 2026-08-26T07:09:16.576Z

### geoip.dat

3 categories · 41,796 entries · 0.40 MB · sha256 `5c4bcba2db02b9df0928f754e79bdc0052c0be085bdb2cea232de9e74122c381`

```
~ DIRECT — 34,881 -> 35,178 (+698 / -401)
```

### geosite.dat

23 categories · 3,531 entries · 0.08 MB · sha256 `5fbe58b44c9464a6d74d00ab0cb1dbdfeb43f1d60866729f3e987f3fed041b41`

```
no change
```
