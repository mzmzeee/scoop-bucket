# mzmzeee's Scoop bucket

Scoop manifests for [a-stack](https://github.com/mzmzeee/a-stack).

```powershell
scoop bucket add mzmzeee https://github.com/mzmzeee/scoop-bucket
scoop install mzmzeee/a-stack
```

Works on Windows 10 and 11, on x64 and ARM64. To keep a-stack running, run `a-stack service install` after installing. Update with `scoop update a-stack`; stop the service first, because Scoop cannot replace a running program.

The manifest is kept in [a-stack's contrib folder](https://github.com/mzmzeee/a-stack/tree/main/contrib/scoop) and copied here for each release.
