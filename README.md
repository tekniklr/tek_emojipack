# tekniklr's emojipack

## instructions, history, and caveats

Slack keeps breaking everything, especially emojipacks and other similar tools.

Currently, the best way I've found to upload emoji to slack in bulk is the use the [Neutral Face Emoji Tools](https://chrome.google.com/webstore/detail/neutral-face-emoji-tools/anchoacphlfbdomdlomnbbfhcmcdmjej/) chrome extension. This will allow you to drag a bunch of emoji into the slack emoji customization panel (providing there is already at least one custom emoji uploaded!), where they will be added with their filenames as the emoji name.

This repo now remains mostly to keep emoji images in a folder ¯\\\_(ツ)\_/¯

Previous instructions for how this repo used to be used follow.

## emojipacks software instructions

See [emojipacks](https://github.com/lambtron/emojipacks) for instructions on how to import these emoji into your slack. The import file is: `https://raw.githubusercontent.com/tekniklr/tek_emojipack/master/tek_emoji.yaml`.

If you have a local copy, run with:
```bash
$ emojipacks -s <subdomain> -e <email> -y tek_emoji.yaml
```

To use the magic of the internet, run with:
```bash
$ emojipacks -s <subdomain> -e <email> -y https://raw.githubusercontent.com/tekniklr/tek_emojipack/master/tek_emoji.yaml
```
