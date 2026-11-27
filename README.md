# Public rule-set artifacts

This repository contains only approved, public rule-set payloads and their source provenance.
It does not contain subscriptions, proxy nodes, credentials, or the Reach source repository.

The GitHub Pages site serves stable files from `site/current/` and immutable snapshots from
`site/releases/<release-id>/`. Verify payload SHA-256 values against each snapshot's `index.json`.
The Stash override at `site/stash/reach-rules.stoverride` registers the current rule providers
without adding routing rules or proxy data. Secret-free device overrides are published under
`site/stash/` as well; their private arguments stay on the subscribing device.
