# AB Protocol Hugo Website

## Set Up

Install [go](https://go.dev/doc/manage-install), install [hugo](https://github.com/gohugoio/hugo#choose-how-to-install)

To get the theme submodule pulled:

```shell
git submodule init

git submodule update
```

## Run

```shell
hugo server -D
```

Leaf structure:

```
./posts/protocol/{leaf}/index.md
```

Branch structure:

```
./posts/protocol/{branch}/_index.md
./posts/protocol/{branch}/{leaf}/index.md
```

## Build

```shell
git submodule update

hugo -D -d docs
```

## Links

- [Hugo Docs: Hugo Quick Start Guide](https://gohugo.io/getting-started/quick-start/)

- [GH: Hugo Docs](https://github.com/gohugoio/hugoDocs)

- [Hugo Docs: Menus](https://gohugo.io/content-management/menus/)

- [Hugo Docs: Hugo PaperMod Theme](https://themes.gohugo.io/themes/hugo-papermod/)

- [PaperMod docs: Installation](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/)

- [PaperMod docs: Example](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite)
