# asciinema2gif

Convert [asciinema](https://asciinema.org/) JSON files to GIF for embedding in Github, Medium, email, Slack and more!

## Installation and Usage

Tested with Python 3.5+

```sh
$ wget https://github.com/diwakergupta/asciinema2gif/blob/master/asciinema2gif.py
$ asciinema rec <path-to-cast.json>
$ python asciinema2gif.py <path-to-cast.json>
# will create <path-to-cast.json.gif>
```

## Requirements

* [Pyte](http://pyte.readthedocs.io/en/latest/): `pip3 install pyte`
* [Pillow](http://pillow.readthedocs.io/en/latest/): `pip3 install pillow`
* [Gifsicle](http://www.lcdf.org/gifsicle/): `brew install gifsicle`

## Examples

![dbxcli](http://dropbox.github.io/dbxcli/images/dbxcli-basics.json.gif)
