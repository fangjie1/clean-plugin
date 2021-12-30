## A clean-plugin for webpack using del

### Installation
```
 npm install clean-plugin -D
```

### Usage
```
const CleanPlugin = require('clean-plugin');

module.exports = {
 
	plugins: [
		new CleanPlugin({exclude: 'a'}),
	]
}
```