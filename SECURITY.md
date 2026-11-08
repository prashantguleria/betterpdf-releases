# Security

Better PDF opens files from anywhere and signs documents with your certificates, so we take
security reports seriously and are grateful for them.

## Reporting a vulnerability

Please email **[hello@evenpine.com](mailto:hello@evenpine.com)** with "Security" in the
subject. Do not open a public issue for a security problem.

Helpful to include:

- the Better PDF version (Better PDF › About Better PDF) and your macOS version,
- what you found and how to reproduce it, with a sample PDF if one is needed (strip anything
  private from it first),
- a **Help › Diagnostics…** zip if it is relevant. Read it before you send it; nothing in it
  leaves your Mac unless you send it.

We aim to reply within a few working days, will keep you told of progress, and credit you in the
release notes if you would like that. Please give us a reasonable time to ship a fix before
you publish details.

## Supported versions

Fixes ship in the newest release. The direct download updates itself through Sparkle (see
the [README](README.md#updates)); the Mac App Store edition updates through the App Store.
Please check that you are on the [latest release](https://github.com/prashantguleria/betterpdf-releases/releases/latest)
before you report.

## In scope

- the Better PDF app, both the direct download and the Mac App Store edition,
- the signed DMGs and checksums published in this repository,
- the update feed at `https://betterpdf.co/appcast.xml` and the licence service at
  `https://betterpdf.co/api/licence/`.

## Verifying what you downloaded

The README explains how to check the checksum, the Developer ID signature and the
notarisation of every release: [Verify the download](README.md#verify-the-download).
