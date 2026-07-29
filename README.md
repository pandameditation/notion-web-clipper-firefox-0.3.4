# notion-web-clipper-firefox-0.3.4
Made Notion web clipper extension work again with Firefox (July 2026)

## Install temporarily
Load it through about:debugging → This Firefox → Load Temporary Add-on.

Permanent installation requires Mozilla signing; unsigned XPIs may still appear “corrupt” in standard Firefox.

## Install permanently

Use AMO unlisted/self-distribution signing:

1. Sign in at Mozilla Developer Hub.
2. Choose Submit a New Add-on → On your own.
3. Upload  notion-web-clipper-0.3.4.xpi .
4. Complete validation and select Firefox Desktop.
5. Download the signed XPI when Mozilla approves it.
6. Open the signed file in Firefox for permanent installation.

Potential blocker: this package contains Notion’s minified proprietary bundle without corresponding source/build instructions. Unlisted extensions are still reviewed, so Mozilla may reject it for missing source, trademark/ownership, or policy reasons.

If rejected, the practical alternatives are temporary loading via about:debugging or using Firefox Developer Edition/Nightly with signature enforcement disabled. Standard Firefox permanently installs only Mozilla-signed extensions.
