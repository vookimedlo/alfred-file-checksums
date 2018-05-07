# alfred-file-checksums
[Alfred 3][1] workflow for computing file checksums.

The most common hash functions are supported.
- MD5
- SHA 1, 256, 384, 512

## Installation

1) Install [alfred-file-checksums workflow.][2]
2) All further updates are handled automatically.

## Usage

Select a file or multiple files in finder and invoke the alfred file actions, by default the <kbd>⌃﻿⌘\\</kbd> shortcut.

![Alfred actions screenshot](doc/images/alfred-actions.png?raw=true "")

Choose the appropriate digest algorithm in displayed menu. Be aware, that a digest computation takes its time on large files, so be patient!
By default, computed digests will be shown. This could be overridden by pressing the ⌘ key, which forces to put computed digests to clipboard.

![Alfred actions submenu screenshot](doc/images/alfred-actions-submenu.png?raw=true "")

Then, by default, the computed digests from selected files will be shown.

![alfred-ffprobe results screenshot](doc/images/alfred-file-checksums-results.png?raw=true "")

[1]: https://www.alfredapp.com/
[2]: https://github.com/vookimedlo/alfred-file-checksums/releases/latest
