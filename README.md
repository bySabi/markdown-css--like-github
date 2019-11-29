# markdown-css--like-github

> CSS file that replicates the markdown styles of Github. Useful for use with modules that convert `MD` and` MDX` files to React components. Like `@next/mdx` or` react-markdown`

## Installation

```bash
# NPM
npm i markdown-css--like-github

# Yarn
yarn add markdown-css--like-github

```

## Usage

1- import CSS

##### from JS

```
import "markdown-css--like-github/index.css"
```

##### from CSS
```
@import "markdown-css--like-github"
```

2- Create a `div` container for the `md` files with `className` *markdown-body*
```
const Markdown = () => (
  <div className="markdown-body">
     <ComponentFromMDFile />
  </div>
)
```


## Credits

### author

- [@bySabi](https://github.com/bySabi)
### original work
- [github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
- gist [tuzz/github](https://gist.github.com/tuzz/3331384)

## Contributing

- Documentation improvement
- Feel free to send any PR

## License

[MIT](./LICENSE)