# Andrey Ryabokon

I build Python and Go tools at IVI for service integration, testing, and predictable caching.

## Tools I maintain

### [Proxy Mock](https://github.com/ivi-ru/proxy_mock) · Python

Simulate HTTP dependencies and inspect requests in integration tests. Configure responses and
response sequences, capture the traffic your service sends, and record real upstream answers to
replay them offline. Run it as a standalone server or through the bundled pytest fixtures.

**Status:** 3.x is the current major; 3.0 changed the administrative API. Requires Python 3.11 or newer.

[Install and usage](https://github.com/ivi-ru/proxy_mock#readme) ·
[Migrating to 3.0](https://github.com/ivi-ru/proxy_mock/blob/main/MIGRATING.md) ·
[PyPI](https://pypi.org/project/proxy-mock/) ·
[Report a problem](https://github.com/ivi-ru/proxy_mock/issues)

### [sanecache](https://github.com/andared/sanecache) · Go

Cache Go values with synchronous writes, byte budgets, and one load per cold key, single or batched.
Use negative caching to remember missing records and TTL jitter to spread out expiration.
No dependencies.

**Status:** pre-1.0; the public API may change. Requires Go 1.24 or newer.

[Quick start](https://github.com/andared/sanecache#quick-start) ·
[API reference](https://pkg.go.dev/github.com/andared/sanecache) ·
[Changelog](https://github.com/andared/sanecache/blob/main/CHANGELOG.md) ·
[Report a problem](https://github.com/andared/sanecache/issues)

## Experimental work

[gomorphy](https://github.com/andared/gomorphy) is my experimental fork of a Russian morphology
library for Go, focused on independent analyzer instances and predictable lifecycle behavior.
See its README for differences from upstream and current limitations.

## Upstream contributions

### [MiniJinja](https://github.com/mitsuhiko/minijinja) · Go port

Changes that bring the Go port in line with Jinja2 and the Rust core, shipped in
[MiniJinja 3.0.0](https://github.com/mitsuhiko/minijinja/blob/3.0.0/CHANGELOG.md#go):

- [Keep whole-number floats from the context as floats](https://github.com/mitsuhiko/minijinja/commit/42c01852).
- [Keep `loop.changed()` state across iterations](https://github.com/mitsuhiko/minijinja/commit/3a301d96).
- [Align floor division and modulo with Jinja2 in Rust and Go](https://github.com/mitsuhiko/minijinja/commit/8356b5f3).
- [Add `Environment.SetUnknownMethodCallback`, matching the Rust API](https://github.com/mitsuhiko/minijinja/commit/7e952a39).
- [Treat empty iterators as empty sequences](https://github.com/mitsuhiko/minijinja/commit/5cad94f7).

For usage questions or bug reports, open an issue in the relevant project with a small example
and the package version. Contributions are welcome; each maintained project has a contributing guide.
