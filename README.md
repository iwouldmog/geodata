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

## This build - v2026.10.07-1323


built 2026-10-07T13:23:53.311Z

### geoip.dat

3 categories · 42,048 entries · 0.40 MB · sha256 `b20db40ffb9efaf4a5a1d742f6a1004d159a44678236d67030f906e0956bdf61`

```
~ DIRECT — 35,329 -> 35,311 (+207 / -225)
```

### geosite.dat

23 categories · 3,922 entries · 0.09 MB · sha256 `cacbef2137c61bb0fa8a9bcaed34613169506c4f65db0b34718dcc6650443f71`

```
no change
```
