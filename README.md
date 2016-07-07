![Slush node-cli Logo](https://github.com/afonsopacifer/slush-node-cli/blob/master/logo.png)

# Slush Node CLI

> A slush generator for Nodejs CLI programs.

## How to install and use the generator?

Install the slush:

```sh
$ [sudo] npm install -g slush
```

Install the node-cli generator:

```sh
$ [sudo] npm install -g slush-node-cli
```

Use the generator:

```sh
$ mkdir myProgram
$ cd myProgram
$ slush node-cli
```

## The generated program

Stack based in NodeJS:

- Generator: [Slush](http://slushjs.github.io/#/)
- Test Framework: [Mocha]()
- Continuous integrations:[TravisCI]()
- Code Quality: [JSHint]()

Folders Structure:

	.
	├── README.md
	├── LICENSE.md
	├── CONTRIBUTING.md
	├── bin/
	|   └── index.js
	├── src/
	|   └── index.js
	├── tests/
	|   └── index.js
	├── package.json
	├── .editorconfig
	├── .jshintrc
	├── .travis.yml
	└── .gitignore

Automatic Tasks:

- `$ npm test`: Run unit tests with mocha.

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [issues](https://github.com/afonsopacifer/slush-node-cli/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/slush-node-cli/blob/master/CONTRIBUTING.md).

## History

See [Releases](https://github.com/afonsopacifer/slush-node-cli/releases) for detailed changelog.

## License

[MIT License](https://github.com/afonsopacifer/slush-node-cli/blob/master/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.com/)
