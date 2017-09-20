# Output directory containing the formatted manuscript

The [`gh-pages`](https://github.com/dhimmel/bitcoin-whitepaper/tree/gh-pages) branch hosts the contents of this directory at https://dhimmel.github.io/bitcoin-whitepaper/.

## Files

This directory contains the following files, which are mostly ignored on the `master` branch:

+ [`index.html`](index.html) is an HTML manuscript.
+ [`github-pandoc.css`](github-pandoc.css) sets the display style for `index.html`.
+ [`manuscript.pdf`](manuscript.pdf) is a PDF manuscript.
+ `*.ots` files are OpenTimestamps which can be used to verify manuscript existence at or before a given time.
  [OpenTimestamps](opentimestamps.org) uses the Bitcoin blockchain to attest to file hash existence.

## Source

The manuscripts in this directory were built from
[`23f72627ca5808651022758912f63eda0c153501`](https://github.com/dhimmel/bitcoin-whitepaper/commit/23f72627ca5808651022758912f63eda0c153501).
