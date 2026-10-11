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

## This build - v2026.10.11-1250


built 2026-10-11T12:50:33.276Z

### geoip.dat

3 categories · 42,056 entries · 0.40 MB · sha256 `a076c0a8118af7fce0f9238a67f83fd4935c91c942bca0738d029bf83efe1ca4`

```
~ DIRECT — 35,318 -> 35,319 (+1 / -0)
```

### geosite.dat

23 categories · 3,922 entries · 0.09 MB · sha256 `cacbef2137c61bb0fa8a9bcaed34613169506c4f65db0b34718dcc6650443f71`

```
no change
```
