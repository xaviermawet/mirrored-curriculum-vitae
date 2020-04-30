# Font Awesome 5 for LaTeX

## How to update `fontawesome5-latest.sty`

1. Download the latest "Font Awesome for Desktop" archive from the official [webiste](https://fontawesome.com/download).
2. Extract latest `*.otf` files into `fonts` directory. Make sure that you replace all spaces with hyphen, e.g `Font Awesome 5 Brands-Regular-400.otf` should become `Font-Awesome-5-Brands-Regular-400.otf`.
3. Extract `icons.json` metadata file.
4. Run `generateFontAwesomeStyle.js` with Node.js to generate a new style file, `fontawesome5-latest.sty`, with the definitions for the latest Font Awesome icons.
```bash
node generateFontAwesomeStyle.js
```
5. Manually replace content of `fontawesome5-latest.sty`.