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

## This build - v2026.11.28-2001


built 2026-11-28T20:01:58.277Z with geodata-studio `184e360`

### geoip.dat

6 categories · 170,729 entries · 2.15 MB · sha256 `97b9395f22d738f9926c0490e3565e888d68dedce6275780ea37bf41ef84a44a`

```
~ DIRECT — 36,155 -> 36,168 (+23 / -10)
```

### geosite.dat

24 categories · 3,947 entries · 0.09 MB · sha256 `201c0c3c681a6484e427d4ae48e43e7ecbf883bb581f02c5a7231eb90e8ca866`

```
no change
```
