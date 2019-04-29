# Crx Builder for webpack (fixed for NodeJs10)
A webpack plugin to package chrome extensions (crx) post build

## Usage

``` javascript
var Crx = require("crx-webpack-plg");
module.exports = {
	plugins: [
		new Crx({
			keyFile: 'key.pem',
			contentPath: 'build',
			outputPath: 'dist',
			name: 'chrome-ext'
		})
	]
}
```

## License

MIT (http://www.opensource.org/licenses/mit-license.php)
