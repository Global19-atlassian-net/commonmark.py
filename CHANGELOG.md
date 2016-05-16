- Fixed a bug where a TypeError could occur, reported by @civalin

## 0.6.4 (2016-05-09)
- The CommonMark spec has been updated to 0.25.
- The HtmlRenderer has been refactored based on upstream changes in commonmark.js.
- Python 2 fixes from @eric-wieser
- Contributions from @funkybob and @hyperknot

## 0.6.3 (2016-01-19)
- CommonMark-py now supports Python 2.6.
- The CommonMark spec has been updated to 0.24.

## 0.6.2 (2016-01-08)
- Fixed a UnicodeEncodeError when parsing unicode entities on
  Python 2. As a result, CommonMark-py now relies on the "future"
  module in Python 2, as documented in setup.py. This can be found on
  pypi: https://pypi.python.org/pypi/future

## 0.6.1 (2016-01-05)
- Fixed an IndexError exception that occurred when input string
  was empty.

## 0.6.0 (2016-01-04)
- CommonMark-py now complies to the 0.23 CommonMark spec
  http://spec.commonmark.org/0.23/
- The ExtensionBlock has been removed in this release, since
  the parser has been rewritten.
- Added a compatibility fix for Python 2.6, but this version
  of Python still isn't really supported.
- `HTMLRenderer` has been renamed to `HtmlRenderer`.
- `DocParser` has been renamed to `Parser`.

## 0.5.5 (2015-12-18)
- Random bug fixes
- Internal code structure changes
- Compatibility fixes for Python 3