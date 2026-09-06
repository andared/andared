# Andrey Ryabokon

I work at IVI and build tools in Python and Go.
My focus is service integration, testing, and predictable runtime behavior.

I care about explicit contracts, useful diagnostics,
and documenting the trade-offs behind an API.

## Projects I maintain

### [sanecache](https://github.com/andared/sanecache) · Go

An in-memory cache with synchronous writes, byte budgets,
TTL jitter, negative caching, and coordinated loading. No dependencies.

**Working toward 1.0.0.** The public API may change before v1;
breaking changes and migration notes are recorded in the changelog.

[Releases](https://github.com/andared/sanecache/releases) ·
[Changelog](https://github.com/andared/sanecache/blob/main/CHANGELOG.md) ·
[Contributing](https://github.com/andared/sanecache/blob/main/CONTRIBUTING.md)

### [Proxy Mock](https://github.com/ivi-ru/proxy_mock) · Python / IVI

An HTTP proxy and mock server for integration tests and local debugging,
with request matching, traffic capture, snapshots, and pytest fixtures.

**Maintaining 2.x and working toward 3.0.0.** The roadmap covers the next
major release, compatibility changes, and the project's scope.

[Releases](https://github.com/ivi-ru/proxy_mock/releases) ·
[Roadmap](https://github.com/ivi-ru/proxy_mock/blob/main/ROADMAP.md) ·
[Changelog](https://github.com/ivi-ru/proxy_mock/blob/main/CHANGELOG.md) ·
[Contributing](https://github.com/ivi-ru/proxy_mock/blob/main/CONTRIBUTING.md)

## Elsewhere in open source

I've proposed improvements to [MiniJinja's](https://github.com/mitsuhiko/minijinja)
Go integration, including these open pull requests:

- [Preserve floating-point values passed through the context](https://github.com/mitsuhiko/minijinja/pull/937).
- [Keep `loop.changed()` state across iterations](https://github.com/mitsuhiko/minijinja/pull/936).

Questions and contributions are welcome in the project issue trackers.
