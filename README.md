# manifest

The [manifest.json](src/manifest_assets/assets/manifest.json) finds place in the `assets` folder.

All files in that particular folder are copied to the root of the distribution folder on `npm run build`.

That's why the [index.html](src/manifest_assets/src/index.html) has a reference to the `manifest.json` that points to the root.

```
 <link rel="manifest" href="/manifest.json" crossorigin="anonymous" />
```
