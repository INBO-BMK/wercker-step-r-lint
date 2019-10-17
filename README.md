# r-lint
[![wercker status](https://app.wercker.com/status/a6266405f5c68221412ef3de88f89c95/m "wercker status")](https://app.wercker.com/project/bykey/a6266405f5c68221412ef3de88f89c95)

A step to run a lintr on an R package.  This is a fork for [Jim Hesters r-lint](https://github.com/jimhester/wercker-step-r-lint).  Best used with one of the
[inbobmk](https://hub.docker.com/u/inbobmk/) images.
```yaml
    - inbobmk/r-lint
```

## Options
* `options` (optional). Options passed to `lintr::lint_package()`.

# License

The MIT License (MIT)

Copyright (c) 2015 Jim Hester

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Changelog

## 0.0.6
- upgrade code to latest devtools

## 0.0.5
- don't upgrade dependencies

## 0.0.4
- assume devtools and lintr are installed

## 0.0.3
- Fix bug with installing package.

## 0.0.2
- Need to install the package to be linted before linting.

## 0.0.1
- initial release
