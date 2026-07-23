# Security policy

## Reporting a vulnerability

Do not open a public issue for a suspected security vulnerability.

Use GitHub's private vulnerability reporting for this repository. Include the
affected version, reproduction steps, impact, and any supporting material that
can be shared safely.

Do not include live API keys, OAuth tokens, passwords, private keys, client
content, or customer data.

## Supported version

Security fixes are delivered through the newest signed release. Update to the
latest available version before reporting behavior that may already have been
addressed.

## Release integrity

Official macOS releases are:

- signed with an Apple Developer ID
- notarized by Apple
- stapled for Gatekeeper verification
- accompanied by SHA-256 checksums
- delivered through this repository and the in-app updater

Stop installation if Gatekeeper reports an unverified or modified application.
