# Change case

Change the case of text on the command line.

Contents:

- [Commands](#commands)
- [Examples](#examples)
- [Implementation](#implementation)
- [Tracking](#tracking)


## Commands

Commands in this repo:

  * [upper-case](bin/upper-case)
  * [lower-case](bin/lower-case)
  * [title-case](bin/title-case)
  * [camel-case](bin/camel-case)
  * [pascal-case](bin/pascal-case)
  * [kebab-case](bin/kebab-case)
  * [snake-case](bin/snake-case)
  * [slug-case](bin/slug-case)
  * [word-case](bin/word-case)


## Examples

Examples of each command:

```sh
$ echo "foo BAR" | upper-case
FOO BAR
```

```sh
$ echo "foo BAR" | lower-case
foo bar
```

```sh
$ echo "foo BAR" | title-case
Foo Bar
```

```sh
$ echo "foo-goo-hoo" | camel-case
fooGooHoo
```

```sh
$ echo "foo-goo-hoo" | pascal-case
FooBarHoo
```

```sh
$ echo "fooGooHoo" | kebab-case
foo-goo-hoo
```

```sh
$ echo "fooGooHoo" | snake-case
foo_goo_hoo
```

```sh
$ echo "Can't Stop Won't Stop" | slug-case
cant-stop-wont-stop
```

```sh
$ echo "Can't Stop Won't Stop" | word-case
Cant_Stop_Wont_Stop
```
 
## Implementation

These scripts use perl because we want these scripts to work on a wide range of systems, including older systems.

These scripts are intended to be simple. 

These scripts are not intended to handle examples such as a title using upper-case content words along with lower-case short words.


## Tracking

* Package: change-case
* Website: http://sixarm.com/change-case
* Cloning: https://github.com/sixarm/change-case
* Version: 3.0.0
* Created: 2017-05-16
* Updated: 2023-10-17T05:56:08Z
* License: GPL-2.0 or GPL-3.0 or contact us for custom
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
* Tracker: 760a85cee2b838f3297f5a5b2bfd9996
