# ui-library

Sass structure guidelines: http://www.sitepoint.com/architecture-sass-project/

## Installation and Usage

The file _assets/stylesheets/main.css_ is generated locally. To see latest changes, set up a sass-watch function that imports: *assets/sass* and exports to: *assets/stylesheets/*





## Setup

This section under heavy modification.

### Requirements

1. Node
1. Ruby
1. Sublime Text 3
  1. _With the following plugins:_
  	1. [Package Control](https://packagecontrol.io/installation)
  	1. [SublimeLinter](http://sublimelinter.readthedocs.org/en/latest/installation.html)
  	1. [Sublime​Linter-contrib-scss-lint](https://packagecontrol.io/packages/SublimeLinter-contrib-scss-lint)
  		* Note: before installing this Linter plugin, `scss-lint` needs to be installed via this Terminal command: `gem install scss-lint`
  1. _And the following User preferences:_  
    * `"tab_size": 2,`
    * `"translate_tabs_to_spaces": true`
1. Metalsmith
	1. `npm install metalsmith`