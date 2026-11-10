# Security Policy

`hcloud-pricetag` runs with a Hetzner Cloud API token that can write to your
project. Reports about anything that could make it write more than the three
price labels, write to a server you did not confirm, or leak the token are the
ones we care most about.

## Reporting a vulnerability

Preferred: **GitHub private vulnerability reporting** on this repository
(Security tab → "Report a vulnerability").

Alternatively: **security@mitjamartini.com**, the same contact as
[Cloud Viewer's security page](https://cloudviewer.app/security/).

Please include what you found and how to reproduce it. You can expect an
acknowledgement within 48 hours and a first assessment within 5 working days.

## Supported versions

Only the latest version on `main` is supported.
