# nodedoc Changelog

## 1.1.3 (not yet released)

(nothing yet)


## 1.1.2

- Pipe the less (PAGER) to avoid the inclusion of the .nodedoc internal detail
  file in the less session.


## 1.1.1

- [issue #1] Use realpath to find deps and doc files relative to nodedoc
  script.


## 1.1.0

- Add support for searching the node.js doc headers for API method matches,
  e.g. `nodedoc fstat`, `nodedoc spawn`. See the README for more info.


## 1.0.3

- Fix `&gt;`, `&lt;` and `&amp;` escapes.


## 1.0.2

- Use "less -R" if no PAGER is set to not get this warning from less:

        ".../fs.nodedoc" may be a binary file.  See it anyway?


## 1.0.1

- Fix paths for npm-installed nodedoc.


## 1.0.0

First release.

