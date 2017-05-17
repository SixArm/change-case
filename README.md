# Change case

Change the case of text on the command line.

Example:

  ```shell
  $ echo "foo BAR" | upper-case
  FOO BAR

  $ echo "foo BAR" | lower-case
  foo bar
 
  $ echo "foo BAR" | title-case
  Foo Bar

  $ echo "foo-bar" | camel-case
  fooBar

  $ echo "fooBar" | snake-case
  foo_bar

  $ echo "fooBar" | chain-case
  foo-bar
  ```
 
## Implementation

These scripts use perl because we want these scripts to work on a wide range of systems, including older systems.

These scripts are intended to be simple. 

These scripts are not intended to handle examples such as a title using upper-case content words along with lower-case short words.


## Tracking

* Package: change-case
* Version: 1.0.0
* Created: 2017-05-16
* Updated: 2017-05-16
* License: GPL
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)

