# tekniklr's emojipack

See [emojipacks](https://github.com/lambtron/emojipacks) for instructions on how to import these emoji into your slack. The import file is: `https://raw.githubusercontent.com/tekniklr/tek_emojipack/master/tek_emoji.yaml`.

If you have a local copy, run with:
```bash
$ emojipacks -s <subdomain> -e <email> -y tek_emoji.yaml
```

To use the magic of the internet, run with:
```bash
$ emojipacks -s <subdomain> -e <email> -y https://raw.githubusercontent.com/tekniklr/tek_emojipack/master/tek_emoji.yaml
```