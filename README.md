# Icon Font Demo

- Clone the repository ('MyFontDemo' is the name you want for the new folder)
```bash
    git clone https://github.com/elrumordelaluz/f-demo.git MyFontDemo
```
- Change the `"name"` attribute in `package.json` file with **the same name** of the new `@font-face`
- Add a `.scss` file with **the same name** of the new `@font-face` in `src/styles` folder
- Add the font files in `src/fonts` folder
- Customize the `config.jade` in `src/templates/partials` with the arrays generated*
- Install the `npm` and `bower` components, then make a firt _build_

```bash
    $ sudo npm install
    $ bower install
    $ gulp #or gulp watch
```

To generate the package:
```bash
   $ gulp pack
```