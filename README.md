# emails
Emails

### Prerequisites:
1. You need to have installed Node.js https://nodejs.org/en/ (make sure to use version 12.16.3 or above, LTS version is preferred).
2. After installation check if node.js and npm are installed run `node -v` and `npm -v`, if you didn't see an error you can clone this repository and use it.

###  How to install:
1. Clone this repository
2. Open terminal in cloned directory
3. Run `npm install` to install dependencies

### How to use
There are few useful NPM scripts.

##### For development:
* `npm run page {template name}` example `npm run page train` this script will set train.mjml template and will allow its use with:
    1. `npm run watch` will watch for changes in MJML template you set in script above and will recompile MJML template into HTML on each change (see folder structure below)
    2. `npm run build` will compile selected MJML template with minified HTML.

### Folder structure
* `templates/` - contains MJML templates
* `content_library/` - contains images for templates.
* `root folder` contains HTMLs which are compiled from MJML templates using npm scripts `watch` and `build`

### Usefull links:
* MJML [documentation](https://mjml.io/documentation/)
* MJML [CLI commands](https://github.com/mjmlio/mjml#command-line-interface)
