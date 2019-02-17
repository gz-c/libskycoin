
[](https://user-images.githubusercontent.com/26845312/32426705-d95cb988-c281-11e7-9463-a3fce8076a72.png)

# Skycoin C library

[![Build Status](https://travis-ci.org/skycoin/libskycoin.svg)](https://travis-ci.org/skycoin/libskycoin)

Skycoin C library (a.k.a `libskycoin`) exports the Skycoin API to DApps using the C programming language.
It is also the foundation to build client libraries for other programming languages.

## Links

* [skycoin.net](https://www.skycoin.net)
* [Skycoin Blog](https://www.skycoin.net/blog)
* [Skycoin Docs](https://www.skycoin.net/docs)
* [Skycoin Blockchain Explorer](https://explorer.skycoin.net)
* [Skycoin Development Telegram Channel](https://t.me/skycoindev)
* [Skycoin Github Wiki](https://github.com/skycoin/skycoin/wiki)

## Subprojects

The Skycoin C library is made of the following components

- `lib/cgo`     : C wrappers for the Skycoin core API
- `lib/swig`    : SWIG interfaces to generate wrappers around the Skycoin core API for other programming languages
- `lib/swagger` : Swagger specifications for generating REST API clients
- `lib/curl`    : C REST client for the Skycoin HTTP API. Generated by [openapi-generator](https://github.com/OpenAPITools/openapi-generator). Powered by [libcurl](https://curl.haxx.se/libcurl/c/).

Consult respective `README` files for further details.
