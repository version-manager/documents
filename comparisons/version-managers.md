# Comparison of Version Managers by Language

## NodeJS

| Name                                                  | `.node-version` | `package.json` | `.nvmrc`        |
|-------------------------------------------------------|-----------------|----------------|-----------------|
| [nvm](https://github.com/nvm-sh/nvm)                  | ✅               | ❌              | ✅               |
| [asdf-nodejs](https://github.com/asdf-vm/asdf-nodejs) | ✅<sup>[1]</sup> | ❌              | ✅<sup>[1]</sup> |
| [rtx](https://github.com/jdxcode/rtx)                 | ✅<sup>[2]</sup> | ❌              | ✅<sup>[2]</sup> |
| [Woof](https://github.com/version-manager/woof)       | ❌               | ❌              | ❌               |
| [n](https://github.com/tj/n)                          | ❔               | ❔              | ❔               |
| [nvm.fish](https://github.com/jorgebucaran/nvm.fish)  | ❔               | ❔              | ❔               |
| [nvmw](https://github.com/hakobera/nvmw)              | ❔               | ❔              | ❔               |
| [avn](https://github.com/wbyoung/avn)                 | ❔               | ❔              | ❔               |
| [fnm](https://github.com/Schniz/fnm)                  | ❔               | ❔              | ❔               |
| [nave](https://github.com/isaacs/nave)                | ❔               | ❔              | ❔               |
| [nodist](https://github.com/nullivex/nodist)          | ❔               | ❔              | ❔               |
| [nodenv](https://github.com/nodenv/nodenv)            | ❔               | ❔              | ❔               |
| [nodebrew](https://github.com/hokaccha/nodebrew)      | ❔               | ❔              | ❔               |

<sup>[1]</sup> [asdf-nodejs/bin/list-legacy-filenames](https://github.com/asdf-vm/asdf-nodejs/blob/master/bin/list-legacy-filenames)

<sup>[2]</sup> [rtx#legacy-version-files](https://github.com/jdxcode/rtx#legacy-version-files)

## Python

| Name                                                         | `.python-version` | `pyproject.toml` |
|--------------------------------------------------------------|-------------------|------------------|
| [pyenv](https://github.com/pyenv/pyenv)                      | ✅                 | ❌                |
| [asdf-python](https://github.com/asdf-community/asdf-python) | ✅<sup>[1]</sup>   | ❌                |
| [rtx](https://github.com/jdxcode/rtx)                        | ✅<sup>[2]</sup>   | ❌                |
| [Woof](https://github.com/version-manager/woof)              | ❌                 | ❌                |
[asdf-python](https://github.com/asdf-vm/asdf-python)
[pyenv](https://github.com/pyenv/pyenv)
[p](https://github.com/qw3rtman/p)
[pvm](https://github.com/DrPandemic/pvm)

<sup>[1]</sup> [asdf-python/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-python/blob/master/bin/list-legacy-filenames)

<sup>[2]</sup> [rtx#legacy-version-files](https://github.com/jdxcode/rtx#legacy-version-files)

## Ruby

| Name                                                | `.ruby-version` | `Gemfile`       |
|-----------------------------------------------------|-----------------|-----------------|
| [rbenv](https://github.com/rbenv/rbenv)             | ✅               | ❌               |
| [rvm](https://github.com/rvm/rvm)                   | ✅               | ❌               |
| [asdf-ruby](https://github.com/asdf-vm/asdf-nodejs) | ✅<sup>[1]</sup> | ✅<sup>[1]</sup> |
| [rtx](https://github.com/jdxcode/rtx)               | ✅<sup>[2]</sup> | ✅<sup>[2]</sup> |
| [Woof](https://github.com/version-manager/woof)     | ❌               | ❌               |
[asdf-ruby](https://github.com/asdf-vm/asdf-ruby)
[rvm](https://rvm.io)
[rbenv](https://github.com/rbenv/rbenv)
[chruby](https://github.com/postmodern/chruby)
[frum](https://github.com/TaKO8Ki/frum)

<sup>[1]</sup> [asdf-ruby/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-ruby/blob/master/bin/list-legacy-filenames)

<sup>[2]</sup> [rtx#legacy-version-files](https://github.com/jdxcode/rtx#legacy-version-files)

## Golang

| Name                                                  | `.go-version`   | `go.mod`        |
|-------------------------------------------------------|-----------------|-----------------|
| [goenv](https://github.com/syndbg/goenv)              | ✅               | ❌               |
| [asdf-golang](https://github.com/asdf-vm/asdf-golang) | ✅<sup>[1]</sup> | ✅<sup>[1]</sup> |
| [rtx](https://github.com/jdxcode/rtx)                 | ✅<sup>[2]</sup> | ✅<sup>[2]</sup> |
| [Woof](https://github.com/version-manager/woof)       | ❌               | ❌               |
| [gvm](https://github.com/moovweb/gvm)
| [stefanmaric/g](https://github.com/stefanmaric/g)
| [voidint/g](https://github.com/voidint/g)
| [goenv](https://github.com/syndbg/goenv)
| [goup](https://github.com/owenthereal/goup)
| [oo](https://github.com/hit9/oo)

<sup>[1]</sup> [asdf-golang/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-golang/blob/master/bin/list-legacy-filenames), with `ASDF_GOLANG_MOD_VERSION_ENABLED=true`

<sup>[2]</sup> [rtx#legacy-version-files](https://github.com/jdxcode/rtx#legacy-version-files)

## Deno

| Name                                                     | `.deno-version` |
|----------------------------------------------------------|-------------|
| [asdf-deno](https://github.com/asdf-community/asdf-deno) | ✅           |
| [justjavac/dvm](https://github.com/justjavac/dvm)        | ✅           |
| [ghosind/dvm](https://github.com/ghosind/dvm)            | ✅           |

## PHP

| Name                                                   | `.php-version` |
|--------------------------------------------------------|-------------|
| [asdf-php](https://github.com/asdf-community/asdf-php) | ✅           |
| [phpenv](https://github.com/phpenv/phpenv)             | ✅           |
| [phpbrew](https://github.com/phpbrew/phpbrew)          | ✅           |
| [php-version](https://github.com/wilmoore/php-version) | ✅           |

## Java

| Name                                              | `.java-version` |
|---------------------------------------------------|-------------|
| [asdf-java](https://github.com/halcyon/asdf-java) | ✅           |
| [sdkman](https://sdkman.io)                       | ✅           |
| [jenv.be](https://www.jenv.be)                    | ✅           |
| [jenv](https://github.com/linux-china/jenv)       | ✅           |
| [jabba](https://github.com/shyiko/jabba)          | ✅           |
