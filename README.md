ct-Font-Awesome-mixins
======================

Workaround for https://github.com/FortAwesome/Font-Awesome/issues/2454

__Please note: this plugin is optimised for internal Chrometoaster use. YMMV.__

## Installation

1. In Terminal: `cd /PATH/TO/PROJECT-THEME-FOLDER`
1. `bower install https://github.com/chrometoasters/ct-Font-Awesome-mixins#v1.0.0 --save`

Note: if you wish to customise where Bower puts installed components, you may add a `.bowerrc` file into this folder:

        {
            "directory" : "PATH/TO/COMPONENTS"
        }

## Usage

    @include icon($fa-var-ICON_NAME);
    
A list of icons is viewable here: http://fortawesome.github.io/Font-Awesome/icons/
