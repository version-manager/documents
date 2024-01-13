# Meta Version Manager Comparison

Meta version managers are generic enough to support multiple languages, unlike "regular" version managers.

Note that systems like [Nix](https://nixos.org) and [Guix](https://guix.gnu.org) are intentionally omitted. They are different systems entirely.

## Support Matrix

| Name                                            | GitHub Stars | Language    | Method | Uses `.tool-versions` |
| ----------------------------------------------- | ------------ | ----------- | ------ | --------------------- |
| [asdf](https://github.com/asdf-vm/asdf)         | 17,000+      | Bash        | Shim   | ✅                     |
| [sdkman](https://github.com/sdkman/sdkman-cli)  | 5,000+       | Bash,Groovy | Shim   | ❌                     |
| [mise](https://github.com/jdxcode/mise)           | 2,000+       | Rust        | PATH   | ✅                     |
| [Hermit](https://github.com/cashapp/hermit)     | 500+         | Go,HCL      | ❔      | ❌                     |
| [aqua](https://github.com/aquaproj/aqua)        | 300+         | Go          | ❔      | ❌                     |
| [proto](https://github.com/moonrepo/proto)      | 163+         | Rust        | ?      | ❌                     |
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

## Custom

## sdkman

- Uses `.sdkmanrc`

## mise

- Uses `.mise.toml`
