# Comparison of Version Managers by Language

## NodeJS

| Name                                                  | Stars  | `.node-version` | `package.json` | `.nvmrc` |
| ----------------------------------------------------- | ------ | --------------- | -------------- | -------- |
| [nvm](https://github.com/nvm-sh/nvm)                  | 67400+ | ✅               | ❌              | ✅        |
| [asdf-nodejs](https://github.com/asdf-vm/asdf-nodejs) | 735+   | ✅[1]            | ❌              | ✅[1]     |
| [mise](https://github.com/jdxcode/mise)               | -      | ✅[2]            | ❌              | ✅[2]     |
| [Woof](https://github.com/version-manager/woof)       | -      | ❌               | ❌              | ❌        |
| [n](https://github.com/tj/n)\[3]                         | 17600+ | ✅               | ✅              | ✅        |
| [nvm.fish](https://github.com/jorgebucaran/nvm.fish)  | 1600+  | ✅               | ❌              | ✅        |
| [avn](https://github.com/wbyoung/avn)                 | 1100+  | ✅               | ❌              | ❔        |
| [fnm](https://github.com/Schniz/fnm)                  | 11900+ | ✅               | ❌              | ✅        |
| [nave](https://github.com/isaacs/nave)\[4]               | 1600+  | ❌               | ❌              | ✅        |
| [nodist](https://github.com/nullivex/nodist)\[5]         | 1500+  | ✅               | ✅              | ❌        |
| [nodenv](https://github.com/nodenv/nodenv)\[6]           | 2000+  | ✅               | ❌              | ❌        |
| [nodebrew](https://github.com/hokaccha/nodebrew)      | 1000+  | ❌               | ❌              | ❌        |
| [nvmw](https://github.com/hakobera/nvmw)              | 672+   | ❌               | ❌              | ❌        |

[1] [asdf-nodejs/bin/list-legacy-filenames](https://github.com/asdf-vm/asdf-nodejs/blob/master/bin/list-legacy-filenames)

[2] [mise#legacy-version-files](https://github.com/jdxcode/mise#legacy-version-files)

[3] `.n-node-version`

[4] `.naverc`

[5] `.npm-version`, `NODIST_NODE_VERSION`, `NODIST_NPM_VERSION`

[6] `NODENV_VERSION`

More info at [node-version-usage](https://github.com/shadowspawn/node-version-usage).

## Python

| Name                                                         | Stars  | `.python-version` | `pyproject.toml` |
| ------------------------------------------------------------ | ------ | ----------------- | ---------------- |
| [pyenv](https://github.com/pyenv/pyenv)                      | 32000+ | ✅                 | ❌                |
| [asdf-python](https://github.com/asdf-community/asdf-python) | 519+   | ✅[1]              | ❌                |
| [mise](https://github.com/jdxcode/mise)                      |        | ✅[2]              | ❌                |
| [Woof](https://github.com/version-manager/woof)              |        | ❌                 | ❌                |
| [p](https://github.com/qw3rtman/p)                           | 772+   | ❌                 | ❌                |

[1] [asdf-python/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-python/blob/master/bin/list-legacy-filenames)

[2] [mise#legacy-version-files](https://github.com/jdxcode/mise#legacy-version-files)

## Ruby

| Name                                                | Stars  | `.ruby-version` | `Gemfile` |
| --------------------------------------------------- | ------ | --------------- | --------- |
| [rbenv](https://github.com/rbenv/rbenv)             | 15100+ | ✅               | ❌         |
| [rvm](https://github.com/rvm/rvm)                   | 4900+  | ✅               | ❌         |
| [asdf-ruby](https://github.com/asdf-vm/asdf-nodejs) | 524+   | ✅[1]            | ✅[1]      |
| [mise](https://github.com/jdxcode/mise)             |        | ✅[2]            | ✅[2]      |
| [Woof](https://github.com/version-manager/woof)     |        | ❌               | ❌         |
| [chruby](https://github.com/postmodern/chruby)      | 2700+  | ✅               | ❌         |
| [frum](https://github.com/TaKO8Ki/frum)             | 542+   | ✅               | ❌         |

[1] [asdf-ruby/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-ruby/blob/master/bin/list-legacy-filenames)

[2] [mise#legacy-version-files](https://github.com/jdxcode/mise#legacy-version-files)

## Golang

| Name                                                 | Stars | `.go-version` | `go.mod` | `.gvm_local` | `GOENV_VERSION` |
| ---------------------------------------------------- | ----- | ------------- | -------- | ------------ | --------------- |
| [asdf-golang](https://github.com/kennyp/asdf-golang) | 367+  | ✅             | ✅[1]     | ❌            | ❌               |
| [mise](https://github.com/jdxcode/mise)              |       | ✅[2]          | ✅[2]     | ❔            | ❔               |
| [Woof](https://github.com/version-manager/woof)      |       | ❌             | ❌        | ❌            | ❌               |
| [gvm](https://github.com/moovweb/gvm)                | 8500+ | ❌             | ❌        | ✅            | ❌               |
| [stefanmaric/g](https://github.com/stefanmaric/g)    | 741+  | ❌             | ❌        | ❌            | ❌               |
| [voidint/g](https://github.com/voidint/g)            | 1100+ | ❌             | ❌        | ❌            | ❌               |
| [goenv](https://github.com/syndbg/goenv)             | 1600+ | ✅             | ✅        | ❌            | ✅               |
| [goup](https://github.com/owenthereal/goup)          | 427+  | ❌             | ❌        | ❌            | ❌               |
| [oo](https://github.com/hit9/oo)                     | 93+   | ❌             | ❌        | ❌            | ❌               |

[1] [asdf-golang/bin/list-legacy-filenames](https://github.com/asdf-community/asdf-golang/blob/master/bin/list-legacy-filenames), with `ASDF_GOLANG_MOD_VERSION_ENABLED=true`

[2] [mise#legacy-version-files](https://github.com/jdxcode/mise#legacy-version-files)

## Deno

| Name                                                     | Stars | `.deno-version` | `.dvmrc` |
| -------------------------------------------------------- | ----- | --------------- | -------- |
| [asdf-deno](https://github.com/asdf-community/asdf-deno) | 108+  | ❌               | ❌        |
| [justjavac/dvm](https://github.com/justjavac/dvm)        | 569+  | ✅               | ✅        |
| [ghosind/dvm](https://github.com/ghosind/dvm)            | 26+   | ✅               | ✅        |

## PHP

| Name                                                   | Stars | `.php-version` | `.phpenv-version` | `PHPENV_VERSION` |
| ------------------------------------------------------ | ----- | -------------- | ----------------- | ---------------- |
| [asdf-php](https://github.com/asdf-community/asdf-php) | 175+  | ❌              | ❌                 | ❌                |
| [CHH/phpenv](https://github.com/CHH/phpenv)            | 570+  | ❌              | ❌                 | ❌                |
| [phpenv/phpenv](https://github.com/phpenv/phpenv)      | 1400+ | ❌              | ✅                 | ✅                |
| [phpbrew](https://github.com/phpbrew/phpbrew)          | 5100+ | ❌              | ❌                 | ❌                |
| [php-version](https://github.com/wilmoore/php-version) | 675+  | ❌              | ❌                 | ❌                |

## Java

| Name                                              | Stars | `.java-version` | `.jabbarc` |
| ------------------------------------------------- | ----- | --------------- | ---------- |
| [asdf-java](https://github.com/halcyon/asdf-java) | 317+  | ✅               | ❌          |
| [sdkman](https://sdkman.io)                       |       | ❌               | ❌          |
| [jenv.be](https://github.com/jenv/jenv)           | 4900+ | ✅               | ❌          |
| [jenv](https://github.com/linux-china/jenv)       | 601+  | ❌               | ❌          |
| [jabba](https://github.com/shyiko/jabba)          | 2600+ | ❌               | ✅          |
