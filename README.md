# TED Classroom Subtitles

A [Stylus](https://github.com/openstyles/stylus) user style that makes TED talk subtitles easier to read on classroom displays and projectors. Choose a subtitle size and subtitle area width in Stylus; the style applies those settings on TED pages.

## Features

- Four subtitle sizes: 24 px, 32 px, 40 px, and 48 px.
- Three subtitle area widths: the original 560 px, 85%, and 95%.
- Settings can be changed in the Stylus style editor without editing CSS.

The defaults are **32 px** and **85%**.

## Install

### Supported browsers

Stylus supports Chrome, Firefox, and Chromium-based browsers. That includes browsers such as Microsoft Edge, Brave, Opera, and Vivaldi; availability depends on the browser's extension store. Check the [official Stylus project page](https://github.com/openstyles/stylus) for current browser and installation options. This stylesheet is intended for TED pages opened in a supported browser with Stylus installed.

### Install the style

1. Install the [Stylus browser extension](https://github.com/openstyles/stylus) from the extension store for your browser, then make sure it is enabled.
2. Open the [raw UserCSS file](https://raw.githubusercontent.com/bostonghc/TED-Classroom-Subtitles/main/ted-classroom-subtitles.user.css) in that browser. Because the link serves the plain `.user.css` file, Stylus should open its style installation page.
3. Review the style name and settings, then click **Install style** in Stylus.
4. Visit a TED talk, turn subtitles on, and check that the style is enabled for `ted.com` in the Stylus extension menu.

To change the subtitle size or width later, open the installed style's configuration in Stylus and save your choices. If the install page does not appear, confirm Stylus is enabled and that you opened the raw stylesheet URL rather than the GitHub file preview. See Stylus's [UserCSS installation instructions](https://github.com/openstyles/stylus/wiki/Writing-UserCSS) for more details.

## Configure

Open the style's settings in Stylus and choose:

| Setting | Options | Default |
| --- | --- | --- |
| Subtitle font size | 24 px, 32 px, 40 px, 48 px | 32 px |
| Subtitle area width | 560 px, 85%, 95% | 85% |

The 40 px and 48 px settings are intended for larger viewing distances. If captions feel crowded, choose a wider subtitle area.

## Compatibility

The style is scoped to `ted.com` and targets the subtitle container and CSS classes used by the TED player. TED may change its page structure or class names; if the style stops applying, inspect the current player markup and update the selectors in the user CSS.

The style only changes subtitle appearance. It does not add subtitles, change TED's playback controls, or alter the underlying video.

## Privacy and network behavior

This is a client-side CSS style. It contains no JavaScript, tracking code, external assets, or network requests. It does not specify or connect to a TED IP address. Stylus applies the rules to the TED page already open in your browser; normal browser traffic to TED to load the page, player, and video still occurs. See [PRIVACY.md](PRIVACY.md) for details.

## Development

Edit `ted-classroom-subtitles.user.css` and reload the style in Stylus to try changes. The UserCSS metadata at the top defines the name, version, and configurable options.

## License

Released under the MIT License. See [LICENSE](LICENSE).
