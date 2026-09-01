# Argus Next.js Fixture v1

This repository is a maintained public fixture for Argus simulation runs. It
provides a small, deterministic Next.js codebase that agents can inspect and
modify in isolated workspaces.

## Provenance

This fixture is a sanitized derivative of
[`gauge-sh/starter-nextjs`](https://github.com/gauge-sh/starter-nextjs) at
commit `82b2639bc9921b598e50e3b18d428744a9da4e0f`. The upstream MIT license is
preserved in [`LICENSE`](LICENSE), with additional provenance in
[`NOTICE`](NOTICE). Gauge does not endorse this fixture or Argus.

## Maintenance policy

Dependencies and fixture behavior remain pinned unless Argus intentionally
publishes and validates a new revision. Simulation catalogues must identify an
exact commit rather than a mutable branch.

## Validate locally

```sh
npm install
npm run lint
npm run build
```
