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

## This build - v2026.10.13-1412


built 2026-10-13T14:12:03.836Z

### geoip.dat

3 categories · 43,112 entries · 0.41 MB · sha256 `b7def768ca674b236383b864a2b319f7fae64f79e2b550c7d584c5cb93ec7331`

```
~ DIRECT — 35,737 -> 36,375 (+843 / -205)
```

### geosite.dat

24 categories · 3,944 entries · 0.09 MB · sha256 `9d70419c2ca25eec77afd96550586497dc7224082f8c640cec9a41e203bf0845`

```
no change
```
