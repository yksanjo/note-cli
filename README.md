# note

One daily note, dead simple.

```
$ note shipped git-streak today
Noted.

$ note
2026-01-08
[14:32] shipped git-streak today

$ note -a
# shows last 7 days
```

## Install

```bash
git clone https://github.com/yksanjo/note-cli.git
chmod +x note-cli/note
cp note-cli/note /usr/local/bin/
```

## Usage

```bash
note <text>   # add note
note          # show today
note -a       # last 7 days
```

Notes stored in `~/.notes/`

## License

MIT
