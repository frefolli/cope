# cope

A coping utility

## Why?

I was coping for a bad vote in uni, so i decided to cope harder

## Usage

This is thought for unix-like systems and their shells.
If you're on Windows, first of all cope, then use it as `python cope`. 

```txt
usage: cope [-h] [-f FILE] [vote]

coping utility

positional arguments:
  vote                  your vote

options:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  path of a csv file with columns (StudentID: int, Vote: int)
```

## Example

There's an example of votes csv file: `votes.csv`. Decide a vote in range `[0, 32]` and run against it with `cope [-f votes.csv] <vote>`.
Default vote is `24`, while default file is `votes.csv`.

NO SPOILERS
