# NVMetrics updates

Compiled, notarized builds of NVMetrics and the update feed (`appcast.xml`) that installed copies of
the app check. The source code is not here.

- Every build is signed with Apple Developer ID, notarized by Apple, and its zip is signed with an
  EdDSA key; the app refuses any update whose signature doesn't match the public key built into it.
- Installed copies check once a day (Settings ▸ Updates, or NVMetrics ▸ Check for Updates…).
- Files here are published by the maintainer's `publish-update.sh`; please don't edit them by hand.
