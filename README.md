# `@flashfix/browserslist-config`

## What is Browserslist?

Share browsers list between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env.

- [Browserslist](https://github.com/ai/browserslist) (Github repo)
- [browserl.ist](http://browserl.ist) (Browserslist query syntax validation)
- ["Browserslist is a Good Idea"](https://css-tricks.com/browserlist-good-idea/) (blog post by [@chriscoyier](https://github.com/chriscoyier))


## Usage

```shell
npm install --save-dev @flashfix/browserslist-config
```

### `.browserslistrc`

```
# Browsers that we support. To see current list: `npx browserslist`

extends @flashfix/browserslist-config
```
