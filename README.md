# Real-Life Patch Notes: The Comedy Changelog

[![make.fun bounty](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![entry rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/KuroriShizuri/patch-notes-real-life-01/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/KuroriShizuri/patch-notes-real-life-01/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

## The entry

What if everyday life shipped software updates? This entry is one
changelog line for the human brain: a fake version number, a fake bug
fix, and a very real 3 a.m. problem. It is the whole submission — a
single funny line, kept exactly as written.

```text
v2.7.1: fixed a bug where the brain replayed embarrassing moments from 2014 at 3 a.m. instead of sleeping.
```

## Running it

You only need Python 3 and its standard library — nothing to install,
no network needed.

```sh
python3 main.py
```

That writes the line to `/output/entry.txt`, with no newline at the
end. To write somewhere else instead, pass `--out`:

```sh
python3 main.py --out result.txt
```

To check the line without writing any file:

```sh
python3 main.py --self-test
```

## Notes

- Before writing anything, the script checks that the line is a single
  line of valid UTF-8 text, between 1 and 160 characters long. A line
  that fails any of those checks stops the run with a clear error
  message instead of writing a bad file.
- Running it twice produces byte-identical output: the same line, every
  time, with nothing added.

---

Built for the make.fun bounty [Real-Life Patch Notes: The Comedy Changelog](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d). Try make.fun yourself: https://make.fun/?ref=1g7byhvf
