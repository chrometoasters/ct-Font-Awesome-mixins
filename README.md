ct-Font-Awesome-mixins
======================

Workaround for https://github.com/FortAwesome/Font-Awesome/issues/2454

__Please note: this plugin is optimised for internal Chrometoaster use. YMMV.__

## Installation

1. In Terminal: `cd /PATH/TO/PROJECT-THEME-FOLDER`
1. `bower install https://github.com/chrometoasters/ct-Font-Awesome-mixins#v1.0.1 --save`

Note: if you wish to customise where Bower puts installed components, you may add a `.bowerrc` file into this folder:

        {
            "directory" : "PATH/TO/COMPONENTS"
        }

## Usage

        // Font Awesome
        $fa-font-path: "../bower_components/Font-Awesome/fonts"; // Font-Awesome/scss/_variables.less, was "../font" (path is relative to css folder)
        @import "../bower_components/Font-Awesome/scss/font-awesome";
        
        // This plugin
        @import "../bower_components/ct-Font-Awesome-mixins/dist/mixins";
        
        // Test styles
        .selector:after {
                @include icon($fa-var-ICON_NAME);
        }

A list of icons is viewable here: http://fortawesome.github.io/Font-Awesome/icons/

## Demo

Please refer to `demos/ct-Font-Awesome-mixins.html`.
