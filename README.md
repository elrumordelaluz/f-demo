# Starting project templatez

First, clone the repository. 'MyTemplate' is the name you want for the folder.

    git clone https://github.com/elrumordelaluz/template-init.git MyTemplate

Then:

    sudo npm install
    bower install
    gulp


It's important to have:
- a .scss file for the @font-face under /styles
- the font files under /fonts
- customize the config.jade file under /templates/partials

To generate the package:

    gulp pack