# TED Classroom Subtitles

A [Stylus](https://github.com/openstyles/stylus) user style that makes TED talk subtitles easier to read on classroom displays and projectors. Choose a subtitle size and subtitle area width in Stylus; the style applies those settings on TED pages.

## Features

- Four subtitle sizes: 24 px, 32 px, 40 px, and 48 px.
- Three subtitle area widths: the original 560 px, 85%, and 95%.
- Settings can be changed in the Stylus style editor without editing CSS.

The defaults are **32 px** and **85%**.

## Install

1. Install Stylus for your browser from the [official Stylus project](https://github.com/openstyles/stylus).
2. Open [`ted-classroom-subtitles.user.css`](ted-classroom-subtitles.user.css) from this repository. On GitHub, select **Raw**; Stylus should offer to install the user style. You can also use the [raw stylesheet URL](https://raw.githubusercontent.com/bostonghc/TED-Classroom-Subtitles/main/ted-classroom-subtitles.user.css).
3. In Stylus, enable the style and visit a TED talk with subtitles turned on.

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

## Development

Edit `ted-classroom-subtitles.user.css` and reload the style in Stylus to try changes. The UserCSS metadata at the top defines the name, version, and configurable options.

## License

Released under the MIT License. See [LICENSE](LICENSE).
