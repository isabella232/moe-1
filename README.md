# moe

A fork of the [eom](https://github.com/mate-desktop/eom/tree/1.16) image viewer (1.16).

## How to build

```
$ ./autogen.sh
$ ./configure \
    --prefix=/usr \
    --localstatedir=/var \
    --with-gtk=2.0 \
    --with-librsvg \
    --disable-python
$ make
$ src/eom -n
```
