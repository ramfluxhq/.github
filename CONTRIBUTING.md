# Contributing to Ramflux

Use the README, contribution guide and CI configuration of the repository you
are changing for its build commands, supported platforms and required checks.
Repository-specific guidance takes precedence over this organisation default.

## Licensing of contributions

- The core repository, `ramflux`, uses BSD-3-Clause. Contributions to the core
  use the same licence (inbound = outbound).
- The client repositories, including `ramflux-tui`, `ramflux-desktop`,
  `ramflux-ios` and `ramflux-android`, use AGPL-3.0-or-later with the applicable
  exception in each repository's `LICENSE`. Contributions to a client follow
  that repository's licence and require its `CLA.md`.
- For other repositories, read their `LICENSE` and licensing guidance before
  contributing. These defaults do not assign the core's licence to other work.
- Every commit requires a DCO sign-off: `git commit -s`. It certifies that you
  wrote the contribution or have the right to submit it; see the
  [Developer Certificate of Origin](https://developercertificate.org).

## Quality and code conventions

Write comments and documentation in English. Use the repository's file headers,
formatters, linters and tests. Source headers must identify the licence applicable
to that file; do not copy BSD headers into AGPL client code. Handle production
errors explicitly and keep input parsing and resource use bounded.

## Pull requests

Keep changes focused and explain their purpose and verification. Add a changelog
entry under `## [Unreleased]` where the repository maintains a changelog. Pass the
repository's required CI checks. Do not include internal hostnames, private
addresses, credentials, personal filesystem paths or internal process records.

## Security

Do not report vulnerabilities in public issues. Follow the repository's
`SECURITY.md`, or the organisation's [security policy](SECURITY.md) when it has no
repository-specific policy.
