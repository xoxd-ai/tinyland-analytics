# tinyland-analytics (RETIRED)

> **Retired 2026-10-09.** This repository is archived and receives no further
> changes. There is no replacement module.

`@tummycrypt/tinyland-analytics` was an MDsveX-based analytics pipeline
(page-view, event and user-activity files written as MDsveX, plus a query
service and a real-time writer). No live app or Bazel registry module depends
on it, so it was retired in the 2026-10 estate uplift (rulings RU2/RU7) rather
than moved to the new stack. Telemetry in the estate goes through OpenTelemetry
(`tummycrypt_tinyland_otel` in the Bazel registry).

- Bazel registry: `tummycrypt_tinyland_analytics` 0.2.2 in
  [xoxd-ai/bazel-registry](https://github.com/xoxd-ai/bazel-registry) is marked
  `deprecated`. It stays resolvable; nothing is yanked.
- npm: no further versions will be published (RU8). Published versions are not
  unpublished.
- Code: the last released source is tag `v0.2.2`. Copy what you need into your
  own app instead of depending on this package.
