# crabnotes

A simple note-taking and searching script for POSIX systems.
[Requires FZF](https://github.com/junegunn/fzf).

## Installation

``` console
~/crabnotes$ mv cnotes /usr/local/bin/
```

## Usage

### Searching notes

``` bash
cnotes
```

This will open an interactive FZF prompt. Crabnotes will display the full note
for whatever heading you select.

### Editing notes

``` bash
cnotes edit
```

This will open the default notes file in your `$EDITOR`. However, if you wish 
to organize your notes in separate files, crabnotes will read from all files in
`~/.config/crabnotes/` so feel free to make as many as you'd like.

You can view the note-file syntax in `sample-notes.md`. Never start any lines
with `#` unless you are denoting a note heading. Furthermore, note headings can
only ever be one line, no more.

