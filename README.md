# hexstr
Encode bytes into a hexstring/Decode a hexstring into bytes

## Usage
```
Usage: hexstr.exe [OPTIONS] [string]

Arguments:
  [string]  Input from the cli arguments. Leave it blank and do not set a file to read from stdin

Options:
  -e, --encode         Encode the input into a hexstring
  -d, --decode         Decode a hexstring
  -f, --file <file>    File to read the input from
  -n, --ommit_newline  Ommit the newline when printing the output. Useful when redirecting the output to a file
  -h, --help           Print help
```
### Examples
Encode the `qwe` string

```
$ hexstr -e qwe
717765
```
Decode the `717765` hexstring

```
$ hexstr -d 717765
qwe
```
