# unheic

*Simple bash script for creating JPEG versions of one or multiple HEIC files.*


## Setup

Copy the `unheic` executable to any location on your [`PATH`](https://en.wikipedia.org/wiki/PATH_(variable)).


## Usage

Run it without any arguments to find out:

```
$ unheic
usage: unheic [--replace] [file ...]
    Create JPEG versions of one or multiple HEIC files which can be located in
    different directories: Each conversion result ends up 'next to' its
    respective original or replaces it if the --replace flag is set. Uses sips.
```


## Notes

The script summons [`sips`](https://ss64.com/osx/sips.html) to do the heavy lifting, so it'll only work on macOS.
