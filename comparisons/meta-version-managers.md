# Meta Version Manager Comparison

Meta version managers are generic enough to support multiple languages, unlike "regular" version managers.

Note that systems like [Nix](https://nixos.org) and [Guix](https://guix.gnu.org) are intentionally omitted. They are different systems entirely.

## Support Matrix

| Name                                            | GitHub Stars | Language    | Method | Uses `.tool-versions` |
| ----------------------------------------------- | ------------ | ----------- | ------ | --------------------- |
| [asdf](https://github.com/asdf-vm/asdf)         | 17,000+      | Bash        | Shim   | ✅                     |
| [mise](https://github.com/jdx/mise)             | 13,000+      | Rust        | PATH   | ✅                     |
| [pkgx](https://github.com/pkgxdev/pkgx)         | 9,200+       | Rust        | ❔     | ❌                     |
| [sdkman](https://github.com/sdkman/sdkman-cli)  | 5,000+       | Bash,Groovy | Shim   | ❌                     |
| [spack](https://github.com/spack/spack)         | 4,500+       | Python      | ❔      | ❌                     |
| [vfox](https://github.com/version-fox/vfox)     | 3,100+       | Go          | ❔      | ✅                     |
| [anyenv](https://github.com/anyenv/anyenv)      | 1,800+       | Bash        | ❔      | ❌                     |
| [vmr](https://github.com/gvcgo/version-manager) | 925+         | Go          | ❔      | ❌                     |
| [Hermit](https://github.com/cashapp/hermit)     | 500+         | Go,HCL      | ❔      | ❌                     |
| [aqua](https://github.com/aquaproj/aqua)        | 300+         | Go          | ❔      | ❌                     |
| [proto](https://github.com/moonrepo/proto)      | 445+         | Rust        | ❔      | ❌                     |
| [Woof](https://github.com/version-manager/woof) | 21+          | Bash,jq     | PATH   | ✅                     |

## Supported Interfaces

| Name                                            | CLI | TUI | GUI |
| ----------------------------------------------- | --- | --- | --- |
| [asdf](https://github.com/asdf-vm/asdf)         | ✅   | ❌   | ❌   |
| [sdkman](https://github.com/sdkman/sdkman-cli)  | ✅   | ❌   | ❌   |
| [mise](https://github.com/jdxcode/mise)           | ✅   | ❔   | ❌   |
| [Hermit](https://github.com/cashapp/hermit)     | ✅   | ❌   | ❌   |
| [aqua](https://github.com/aquaproj/aqua)        | ✅   | ✅   | ❌   |
| [proto](https://github.com/moonrepo/proto)      | ✅   | ❔   | ❔   |
| [Woof](https://github.com/version-manager/woof) | ✅   | ✅   | ❌   |
| [vmr](https://github.com/gvcgo/version-manager) | ✅   | ✅   | ❌   |

## Custom

### sdkman

- Uses `.sdkmanrc`

### mise

- Uses `.mise.toml`

### proto

[It checks in order:](https://moonrepo.dev/docs/proto/detection)

- CLI argument
- `PROTO_*_VERSION` environment variable
- `.prototools` (local)
- version manager configs (e.g. `.nvmrc`) & manifest files (e.g. `package.json`)
- `~/.proto/.prototools` (global)
