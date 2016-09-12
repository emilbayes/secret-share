# `secret-share` [WIP]

> Split secrets for secure sharing! Pure JavaScript implementation of [`libgfshare`](http://www.digital-scurf.org/software/libgfshare)

## Install

```js
npm install gfshare
```

## Usage

## CLI

```sh
secret-split --threshold=3 --shares=5 secret.txt
```

```sh
secret-combine share.001 share.002 share.003
```

## License

Original C implementation by Daniel Silverstone.  
[ISC](LICENSE.md)
