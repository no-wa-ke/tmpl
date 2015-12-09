# Changelog for riot-tmpl

### v2.3.15
- Fix [riot#1416](https://github.com/riot/riot/issues/1416): Issue with space in expression of `each`.
- Fix: when calling the compiler with different brackets, `brackets.array` changes the global configuration (`riot.settings.brackets`).

### v2.3.14
- Fix #11: Can't output expressions without evaluation.
- Fixed issues with regex detection in brackets.js and revision of other regexes.
- Fixed issues with istanbul and new versions of npm in the Makefile.
- Revision of devDependencies, including istanbul for npm 2/3 compatibility.
- Preparation for recognize the raw-html flag `=` (can change in the final implementation).
- Preparation for use as ES6 module through [rollup.js](http://rollupjs.org/)
- Removed internal functions from the documentation.
- Updated tests.