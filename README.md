gopngquant
==========

A library to compress PNG files using [imagequant][1].

## Usage

- Command line

```sh
go get -u github.com/manhtai/gopngquant/cmd/pngquant
pngquant -i input.png -o output.png
```

## batch rename

```sh
for f in *.png ; do pngquant -i "$f" -o "${f%.*}_.png" ; done
```


- As a library

[Documentation][2]
[Create your own context menu item in OSX][3]


[1]: https://github.com/manhtai/imagequant
[2]: https://godoc.org/github.com/manhtai/gopngquant
[3]: https://davidwalsh.name/mac-context-menu
