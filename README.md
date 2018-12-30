# Change case

Change the case of text on the command line.

Contents:

* [Commands](#commands)
* [Examples](#examples)
* [Implementation](#implementation)
* [Tracking](#tracking)


## Commands

Commands in this repo:

  * [upper-case](bin/upper-case)
  * [lower-case](bin/lower-case)
  * [title-case](bin/title-case)
  * [camel-case](bin/camel-case)
  * [pascal-case](bin/pascal-case)
  * [snake-case](bin/snake-case)
  * [chain-case](bin/chain-case)
  * [token-case](bin/token-case)
  * [slug-case](bin/slug-case)


## Examples

Examples of each command:

```shell
$ echo "foo BAR" | upper-case
FOO BAR

$ echo "foo BAR" | lower-case
foo bar
 
$ echo "foo BAR" | title-case
Foo Bar

$ echo "foo-bar" | camel-case
fooBar

$ echo "foo-bar" | pascal-case
FooBar

$ echo "fooBar gooCar" | snake-case
foo_bar goo_car

$ echo "fooBar" | chain-case
foo-bar

$ echo "Can't Stop Won't Stop" | token-case
cant_stop_wont_stop
  
$ echo "Can't Stop Won't Stop" | slug-case
cant-stop-wont-stop
```

 
## Implementation

These scripts use perl because we want these scripts to work on a wide range of systems, including older systems.

These scripts are intended to be simple. 

These scripts are not intended to handle examples such as a title using upper-case content words along with lower-case short words.


## Tracking

* Package: change-case
* Website: http://sixarm.com/change-case
* Cloning: https://github.com/sixarm/change-case
* Version: 2.2.0
* Created: 2017-05-16
* Updated: 2018-12-18
* License: GPL
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
* Tracker: 760a85cee2b838f3297f5a5b2bfd9996
