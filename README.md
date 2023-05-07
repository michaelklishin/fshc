# fshc: a File and Socket Handle Counter

A tiny command line tool that prints file and socket descriptor (handle)
counts for a process.

## Supported Operating Systems

 * Linux
 * macOS

Windows is not supported at the moment.

## Usage

``` shell
# formats the output using 'jq'
fshc --pid 73847 | jq
```

## License

This tool is dual-licensed under the ASL2 and MIT licenses.