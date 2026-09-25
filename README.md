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

## This build - v2026.09.25-1151


built 2026-09-25T11:51:33.298Z

### geoip.dat

3 categories · 42,666 entries · 0.41 MB · sha256 `0f87318ea251e87dcd4688687974bec986593e01ec8f5a9d902f478b2d2a45fe`

```
~ DIRECT — 35,949 -> 35,929 (+21 / -41)
```

### geosite.dat

23 categories · 3,921 entries · 0.09 MB · sha256 `7ebf2f9184af858e760787495df664418512336a2e6e3dbd615119ba0eade982`

```
no change
```
