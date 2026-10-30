# Sylphx Scoop bucket

Install anymd, repomap and lockdocs on 64-bit Windows with [Scoop](https://scoop.sh):

```powershell
scoop bucket add sylphx https://github.com/SylphxAI/scoop-bucket
scoop install sylphx/anymd sylphx/repomap sylphx/lockdocs
anymd version
repomap version
lockdocs version
```

The manifests use each tool's existing GitHub release archive and SHA-256 digest, rendered with `SylphxAI/mcp-kit/scripts/package-managers.mjs`. AnyAgents has no native Windows release or Scoop manifest.
