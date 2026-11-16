# PocketBase mirror

This is **PocketHost's maintained mirror of [PocketBase](https://ganigeorgiev.com/pocketbase/pocketbase)**.

PocketHost keeps it current, and PocketHost and [PocketOne](https://github.com/pockethost/pocketone) build on it. It is
**not** PocketBase's own repository. PocketBase is written by Gani Georgiev and lives at
[ganigeorgiev.com/pocketbase/pocketbase](https://ganigeorgiev.com/pocketbase/pocketbase), which is the source of truth.
PocketBase doesn't publish a GitHub mirror itself, and PocketHost is not affiliated with or endorsed by PocketBase or
Gani Georgiev.

## What's here

- Every branch and tag of PocketBase (`master`, `develop`, `v0.42.2`, ...), exactly as upstream has them.
- Refreshed once a day by [`.github/workflows/mirror.yml`](.github/workflows/mirror.yml) on this branch.
- Fast-forward only: if upstream ever rewrites a branch or moves a tag, the run fails and a person looks at it. Nothing
  here is ever force-pushed over upstream's history.
- This `mirror` branch is the only thing PocketHost adds. Upstream's code never changes here.

To use it as a remote:

```
git remote add pocketbase https://github.com/pockethost/pocketbase.git
```

Go code still imports PocketBase by its own module path, `ganigeorgiev.com/pocketbase/pocketbase`.

## Issues and changes

Report PocketBase bugs and send changes to PocketBase upstream, not here. Issues are off on this repository.

## License

PocketBase is MIT licensed, Copyright (c) 2022 - present, Gani Georgiev. See `LICENSE.md` on any mirrored branch.
