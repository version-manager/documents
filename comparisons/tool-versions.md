# Support for `.tool-versions`

- asdf [documentation](https://asdf-vm.com/manage/configuration.html#tool-versions)
- mise [documentation](https://github.com/jdxcode/mise#misetoml)
- Woof [documentation](https://github.com/version-manager/woof/blob/main/docs/details.md)

## Supported Features

| Name                                            | Comments | Latest          | Fallback Versions | Fuzzy Versions  | lts             | system          |
|-------------------------------------------------|----------|-----------------|-------------------|-----------------|-----------------|-----------------|
| [asdf](https://github.com/asdf-vm/asdf)         | ✅        | ✅               | ✅                 | ❌               | ❔               | ✅               |
| [mise](https://github.com/jdxcode/mise)           | ✅        | ✅               | ❌                 | ✅               | ✅               | ✅               |
| [Woof](https://github.com/version-manager/woof) | ✅        | ❌[1] | ✅                 | ❌[1] | ❌[1] | ❌[1] |

[1] Planned

## Supported Protocols

Strings in the format of `<protocol>:<value>`:

| Name                                            | `ref:` protocol | `prefix:` protocol | `path:` protocol   |
|-------------------------------------------------|-----------------|--------------------|--------------------|
| [asdf](https://github.com/asdf-vm/asdf)         | ✅               | ✅                  | ✅[1][2] |
| [mise](https://github.com/jdxcode/mise)           | ✅               | ✅                  | ✅                  |
| [Woof](https://github.com/version-manager/woof) | ❌[3] | ❌[3]    | ❌[3]    |

[1] Supported `~/` since [v0.11.1](https://github.com/asdf-vm/asdf/commit/670c96d1a6d6d2c19ff63ce2ed14f784c340e9b9)

[2] Does not support whitespace in path

[3] Planned

## Extras

### mise

#### `!-<difference>` (experimental)

Install a version behind a particular point

- Example: `node lts!-2`
  - Install 2 versions behind latest lts

- Example: `python latest!-0.1`
  - Install Python 3.10 if the latest if 3.11
