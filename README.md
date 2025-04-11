# bqr

## Styles

### Install Less globally

```sh
npm install -g less
```

### Install Minify globally

```
npm install less-plugin-clean-css -g
```

### Compile `styles.less` to `styles.css`

```sh
lessc styles.less styles.css
```

### Watch `.less` files and compile them automatically

```sh
npx nodemon --ext less --exec "lessc styles.less styles.css --clean-css"
```

### Notes

1. **SHOP NAV** - bold
2. **SHOP NAV** - static menu - last item
3. **How to implement SVG**
4. **PROFILE - HISTORY - > BUTTON** - icon button or whole element?
5. **WHAT** LINK TO profile-login.html?
6. **Preco** v register forme nie je back button biely?

### Fonts

LATO nema dobre makcene,
u nas v robte je kombinaciaLato/Inter

logo: Gabarito - 500
h1,h2:Lato, "Open Sans", sans-serif; - 400,600
text: "Inter", sans-serif; - 400,600
