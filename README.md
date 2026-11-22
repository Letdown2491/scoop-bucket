# scoop-bucket

Scoop bucket for [noscat](https://github.com/Letdown2491/noscat).

```
scoop bucket add letdown2491 https://github.com/Letdown2491/scoop-bucket
scoop install noscat
```

The manifest in `bucket/noscat.json` is updated by the noscat release
workflow after every tag push (sha256s come straight from the release
artifacts), so `scoop update*` picks up new versions automatically.
