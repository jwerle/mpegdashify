mpegdashify
===========

Simple `MP4Box` wrapper that adds sane defaults for generating a `MPD`
MPEG-DASH manifest file with segments. This module supports `.m3u8`
extension input and defaults to a `4000` duration with `4000` as the
`-frag` value

## Installation

```sh
$ [sudo] npm install mpegdashify -g
```

## Usage

```sh
usage: mpegdashify [...options] <input>
```

## Example

```sh
# transform HLS transport streams into segments
$ dashify -out big-buck-bunny.mpd /path/to/hls/*.ts
```

## License

MIT
