# Support for `.tool-versions`

- asdf [documentation](https://asdf-vm.com/manage/configuration.html#tool-versions)
- mise-en-place (formerly rtx) [documentation](https://mise.jdx.dev/)
- Woof [documentation](https://github.com/version-manager/woof/blob/main/docs/details.md)

## Supported Features

| Name                                                        | Comments | Latest          | Fallback Versions | Fuzzy Versions  | lts             | system          |
|-------------------------------------------------            |----------|-----------------|-------------------|-----------------|-----------------|-----------------|
| [asdf](https://github.com/asdf-vm/asdf)                     | ✅        | ✅               | ✅                 | ❌               | ❔               | ✅               |
| [mise-en-place (formerly rtx)](https://github.com/jdx/mise) | ✅        | ✅               | ❌                 | ✅               | ✅               | ✅               |
| [Woof](https://github.com/version-manager/woof)             | ✅        | ❌<sup>[1]</sup> | ✅                 | ❌<sup>[1]</sup> | ❌<sup>[1]</sup> | ❌<sup>[1]</sup> |

<sup>[1]</sup> Planned

## Supported Protocols

Strings in the format of `<protocol>:<value>`:

| Name                                                        | `ref:` protocol | `prefix:` protocol | `path:` protocol   |
|-------------------------------------------------            |-----------------|--------------------|--------------------|
| [asdf](https://github.com/asdf-vm/asdf)                     | ✅               | ✅                  | ✅<sup>[1][2]</sup> |
| [mise-en-place (formerly rtx)](https://github.com/jdx/mise) | ✅               | ✅                  | ✅                  |
| [Woof](https://github.com/version-manager/woof)             | ❌<sup>[3]</sup> | ❌<sup>[3]</sup>    | ❌<sup>[3]</sup>    |

<sup>[1]</sup> Supported `~/` since [v0.11.1](https://github.com/asdf-vm/asdf/commit/670c96d1a6d6d2c19ff63ce2ed14f784c340e9b9)

<sup>[2]</sup> Does not support whitespace in path

<sup>[3]</sup> Planned

## Extras

### mise-en-place (formerly rtx)

#### `!-<difference>` (experimental)

Install a version behind a particular point

- Example: `node lts!-2`
  - Install 2 versions behind latest lts
- Example: `python latest!-0.1`
  - Install Python 3.10 if the latest if 3.11
