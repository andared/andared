# Andrey Ryabokon

I build Python and Go tools at IVI for service integration, testing, and predictable caching.

## Tools I maintain

### [Proxy Mock](https://github.com/ivi-ru/proxy_mock) · Python

Simulate HTTP dependencies and inspect requests in integration tests. Configure responses,
capture traffic, and reuse mock snapshots through a standalone server or the bundled pytest fixtures.

**Status:** maintained 2.x releases. Requires Python 3.11 or newer.

[Install and usage](https://github.com/ivi-ru/proxy_mock#readme) ·
[PyPI](https://pypi.org/project/proxy-mock/) ·
[Report a problem](https://github.com/ivi-ru/proxy_mock/issues)

### [sanecache](https://github.com/andared/sanecache) · Go

Cache Go values with synchronous writes, byte budgets, and coordinated loading of missing keys.
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

## Contributions

Recent proposed improvements to MiniJinja's Go integration:

- [Preserve floating-point values passed through the context](https://github.com/mitsuhiko/minijinja/pull/937).
- [Keep `loop.changed()` state across iterations](https://github.com/mitsuhiko/minijinja/pull/936).

For usage questions or bug reports, open an issue in the relevant project with a small example
and the package version. Contributions are welcome; each maintained project has a contributing guide.
