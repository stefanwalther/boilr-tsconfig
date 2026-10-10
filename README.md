# boilr-tsconfig

> A tsconfig.json template for boilr.

> **Retired:** boilr templates predate AI coding tools and no longer make sense. This repository is archived read-only and will receive no further updates.

---

## Purpose
A tsconfig.json template for boilr.

The following files are generated:

```
.
`-- tsconfig.json

0 directories, 1 file

```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first.

Then use

```
$ boilr download stefanwalther/boilr-tsconfig <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-tsconfig boilr-tsconfig
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-tsconfig <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-tsconfig
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g.
$ boilr template save $(PWD) tsconfig
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-tsconfig .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects
Some related projects:

- [stefanwalther/boilr-editorconfig](https://github.com/stefanwalther/boilr-editorconfig)
- [stefanwalther/boilr-gitignore](https://github.com/stefanwalther/boilr-gitignore)

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)
* [github.com/stefanwalther](http://github.com/stefanwalther)

### License
MIT
