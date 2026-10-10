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

## This build - v2026.10.10-1232


built 2026-10-10T12:32:31.677Z

### geoip.dat

3 categories · 42,055 entries · 0.40 MB · sha256 `09f87bbb057e4ad216b59d3fa614df4c9483de6ea856077c18b7cf6046f56907`

```
~ DIRECT — 35,315 -> 35,318 (+3 / -0)
```

### geosite.dat

23 categories · 3,922 entries · 0.09 MB · sha256 `cacbef2137c61bb0fa8a9bcaed34613169506c4f65db0b34718dcc6650443f71`

```
no change
```
