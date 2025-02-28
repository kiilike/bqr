# bqr

## Styles

To install Less globally:

```sh
npm install -g less
```

To compile `styles.less` to `styles.css`:

```sh
lessc styles.less styles.css
```

To watch `.less` files and compile them automatically:

```sh
npx nodemon --ext less --exec "lessc styles.less styles.css"
```
