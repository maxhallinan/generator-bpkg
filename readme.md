# generator-bpkg

Generate a module that targets a browser environment.


## Install

```
$ npm install --global yo generator-bpkg
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo bpkg
```

There are multiple command-line options available:

```
$ yo bpkg --help

  Usage:
    yo nm [options]

  Options:
    -h,   --help    # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers             Default: false
    --skip-install  # Do not automatically install dependencies  Default: false
    --org           # Publish to a GitHub organization account
```

The `--org` option takes a string value (i.e. `--org=foo`). All others are boolean
flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be
prompted for any options not passed on the command-line.


## License

MIT © [Max Hallinan](https://github.com/maxhallinan)