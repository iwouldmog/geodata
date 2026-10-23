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

## This build - v2026.10.23-1139


built 2026-10-23T11:39:20.050Z with geodata-studio `184e360`

### geoip.dat

4 categories · 43,143 entries · 0.41 MB · sha256 `9e157f09b67c0668ea1faf2794585aa19cc8d0c124ed80360a70adf9c591ff58`

```
~ DIRECT — 36,421 -> 36,398 (+60 / -83)
~ PRIVATE — 28 -> 29 (+1 / -0)
```

### geosite.dat

24 categories · 3,945 entries · 0.09 MB · sha256 `3b93ce15e2c527c18642266921592fe2ee296d54a63f0ead76ae7e0ec83de7fe`

```
no change
```
