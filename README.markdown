# strtod for Rust

Apache 2.0 License.

## Introduction

`strtod` is a floating point parsing implementation for Rust with very
high precision, far better than the built in Rust floating point parser.

The documentation can be found at http://pvginkel.github.io/strtod/stdtod/index.html.

## Remarks

The quality of the source is not really something to write home about.
The reason for this is that this implementation is a verbatim translation
from http://mxr.mozilla.org/mozilla-central/source/js/src/dtoa.c.
That being said, the quality of the parser itself is very high.

The performance of this implementation should be OK. However there is room
for improvement in the BigNum implementation that the parser uses, e.g.
by caching instances or calculations. The original implementation does
this, but this has been removed from this implementation.

## Bugs

Bugs should be reported through github at
[http://github.com/pvginkel/strtod/issues](http://github.com/pvginkel/strtod/issues).

## License

PdfiumViewer is licensed under the Apache 2.0 license. See the license details for how PDFium is licensed.