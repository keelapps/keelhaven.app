# keelhaven-site

Published website and documentation for [Keelhaven](https://github.com/keelapps),
a privacy-first backup app for macOS.

The site it serves is live at **https://keelhaven.app**.

This repository exists **only** to serve the site via GitHub Pages. The
`gh-pages` branch is generated and force-pushed by CI from a private source
repository — do not open PRs against it; they will be overwritten. That
includes the `CNAME` file that attaches the custom domain: it is generated
too, and editing it here will not survive the next deploy.

## Copyright

© Keelapps. All rights reserved. Keelapps' own content in this repository is
made public solely for deployment purposes; no license is granted to copy,
modify, or redistribute it.

That claim covers Keelapps' material only. The published site also carries
third-party open source material, which remains under its own license and is
not restricted by the paragraph above — currently the BSD 2-Clause text for
[restic](https://restic.net), © 2014 Alexander Neumann, which Keelhaven
bundles and redistributes. See the site's
[open source licenses](https://keelhaven.app/licenses)
page for the full notice.
