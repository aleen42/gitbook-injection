## injection

[![Pay](https://img.shields.io/badge/%24-free-%23a10000.svg)](#) [![GitHub issues](https://img.shields.io/github/issues/aleen42/gitbook-injection.svg)](https://github.com/aleen42/gitbook-injection/issues) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/aleen42/gitbook-injection/master/LICENSE) [![Gitter](https://badges.gitter.im/aleen42/gitbook-injection.svg)](https://gitter.im/aleen42/gitbook-injection?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[![npm](https://img.shields.io/npm/v/gitbook-plugin-injection.svg)](https://www.npmjs.com/package/gitbook-plugin-injection) [![Build Status](https://travis-ci.org/aleen42/gitbook-injection.svg?branch=master)](https://travis-ci.org/aleen42/gitbook-injection) [![devDependency Status](https://david-dm.org/aleen42/gitbook-injection/dev-status.svg)](https://david-dm.org/aleen42/gitbook-injection#info=devDependencies) [![npm](https://img.shields.io/npm/dt/gitbook-plugin-injection.svg)](https://www.npmjs.com/package/gitbook-plugin-injection)

a gitbook-plugin for inject script into your books.

#### Installation

add the following plugins to your `book.json` and run `gitbook install`

```json
{
    "plugins": ["injection"]
}
```

#### Usage

just find plugin on gitbook and install it on your gitbook project.

configuration option can be set as an obj like:

```json
{
	"plugins": [
		"injection"
	],
	"pluginsConfig": {
		"injection": {
			"js": [
                "./index.js",
                "./content.js"
            ],
            "css": [
                "./../style.css",
                "normal.css"
            ]
		}
	}
}
```

#### Tests

```bash
npm test
```

#### Release History

* ==================== **1.0.0 Initial release** ====================
	* 1.0.1 fix bugs of Gitbook engine 3.0.3

#### :fuelpump: How to contribute

Have an idea? Found a bug? See [how to contribute](https://aleen42.gitbooks.io/personalwiki/content/contribution.html).

#### :scroll: License

[MIT](https://aleen42.gitbooks.io/personalwiki/content/MIT.html) © aleen42
