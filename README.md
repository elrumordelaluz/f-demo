# Starting project templatez

First, clone the repository. 'MyFontDemo' is the name you want for the folder.

    git clone https://github.com/elrumordelaluz/f-demo.git MyFontDemo

Then:

    sudo npm install
    bower install
    gulp


Remember to edit the "name" attribute of the `package.json` file with the same name of the generated font.

It's important to have:
- a `.scss` file for the _@font-face_ under `/styles`
- the font files under `/fonts`
- customize the `config.jade` file under `/templates/partials`

To generate the package:

    gulp pack