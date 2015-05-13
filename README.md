dotenv
======

Load environment variables at runtime from a `.env` file.

[![Pub Version][pub-badge]][pub]
[![Build Status][ci-badge]][ci]
[![Documentation][dartdocs-badge]][dartdocs]

[ci-badge]: https://travis-ci.org/mockturtl/dotenv.svg?branch=master
[ci]: https://travis-ci.org/mockturtl/dotenv
[pub-badge]: https://img.shields.io/pub/v/dotenv.svg
[pub]: https://pub.dartlang.org/packages/dotenv
[dartdocs-badge]: https://img.shields.io/badge/dartdocs-reference-blue.svg
[dartdocs]: http://www.dartdocs.org/documentation/dotenv/latest

### usage

See [documentation][dotenv-usage].

[dotenv-usage]: http://www.dartdocs.org/documentation/dotenv/latest/index.html#dotenv/dotenv

### cli

Get the latest:

```sh
$ pub global activate dotenv
```

Run:

```sh
$ pub global run dotenv:new  # create a `.env` file and add it to `.gitignore`
$ pub global run dotenv      # load the file and print the environment to stdout
```

### limitations

Variable substitution and character escaping is a work in progress.  Some cases don't work yet.  Pull requests gleefully considered.

###### prior art

- [bkeepers/dotenv][] (ruby)
- [motdotla/dotenv][] (node)
- [theskumar/python-dotenv][] (python)
- [joho/godotenv][] (golang)
- [slapresta/rust-dotenv][] (rust)
- [chandu/dotenv][] (c#)
- [tpope/lein-dotenv][], [rentpath/clj-dotenv][] (clojure)
- [mefellows/sbt-dotenv][] (scala)
- [greenspun/dotenv][] (half of common lisp)

[bkeepers/dotenv]: https://github.com/bkeepers/dotenv
[motdotla/dotenv]: https://github.com/motdotla/dotenv
[theskumar/python-dotenv]: https://github.com/theskumar/python-dotenv
[joho/godotenv]: https://github.com/joho/godotenv
[slapresta/rust-dotenv]: https://github.com/slapresta/rust-dotenv
[chandu/dotenv]: https://github.com/Chandu/DotEnv
[tpope/lein-dotenv]: https://github.com/tpope/lein-dotenv
[rentpath/clj-dotenv]: https://github.com/rentpath/clj-dotenv
[mefellows/sbt-dotenv]: https://github.com/mefellows/sbt-dotenv
[greenspun/dotenv]: https://www.youtube.com/watch?v=pUjJU8Bbn3g
