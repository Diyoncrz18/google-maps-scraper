# Remove NetNut Design

## Goal

Remove every current-tree appearance of the NetNut proxy provider while preserving the generic sponsorship and proxy recommendation systems.

## Changes

- Remove the NetNut sponsor block from `README.md`.
- Remove the NetNut row from `docs/proxies.md`.
- Remove the NetNut entry from the proxy sponsor registry.
- Delete the dedicated `netnut.md` sponsor page.
- Delete the `img/netnut-banner.png` asset.

No other sponsor content, provider-selection logic, or proxy behavior will change.

## Verification

- Search tracked and untracked repository content and filenames case-insensitively for `netnut` and `net nut`.
- Validate the sponsor registry through the existing selector tests.
- Run relevant repository checks for the changed documentation and registry content.
