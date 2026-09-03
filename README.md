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

## This build - v2026.09.03-1115


built 2026-09-03T11:15:01.014Z

### geoip.dat

3 categories · 42,383 entries · 0.41 MB · sha256 `5fe72eb5b3c5456a7fdc59378a3beb4ca320bd29f2b63beca6a7390ae2653726`

```
~ DIRECT — 35,682 -> 35,646 (+602 / -638)
```

### geosite.dat

23 categories · 3,921 entries · 0.09 MB · sha256 `7ebf2f9184af858e760787495df664418512336a2e6e3dbd615119ba0eade982`

```
no change
```
