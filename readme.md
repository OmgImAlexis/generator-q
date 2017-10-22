# generator-q [![Build Status](https://travis-ci.org/omgimalexis/generator-q.svg?branch=master)](https://travis-ci.org/omgimalexis/generator-q)

> Scaffold out a node module

This is what I use for [my own modules](https://www.npmjs.com/~omgimalexis).

![](screenshot.png)


## Install

```
$ npm install --global yo generator-q
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo q
```

There are multiple command-line options available:

```
$ yo q --help

  Usage:
    yo q [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
