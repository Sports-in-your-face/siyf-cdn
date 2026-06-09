# siyf-cdn

Static JSON and media for [Sports in your face!](https://github.com/Sports-in-your-face). Production serves via [jsDelivr](https://www.jsdelivr.com/?docs=gh).

## CDN URL

```
https://cdn.jsdelivr.net/gh/Sports-in-your-face/siyf-cdn@main
```

Used by `siyf-chrome`, `siyf-engine`, and the extension at runtime for team logos, registry JSON, and special-event catalogs.

## Sync from monorepo

```bash
# From Sports in your face! workspace
npm run sync:cdn --prefix siyf-chrome
cd siyf-cdn && git add -A && git commit -m "Sync CDN assets" && git push
```

## Org

Maintained under [**Sports-in-your-face**](https://github.com/Sports-in-your-face) by [@nicholasxdavis](https://github.com/nicholasxdavis).
