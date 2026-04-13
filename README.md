# fj — Fuzzy directory stack navigator

Fuzzy searches directories and pushes the best match to your shell's dirstack.

It's called fj because fj is really easy to type.

It does not stand for file jockey/jumper unless you want it to.

This is great for monorepo navigation.

## Usage

```bash
# Let's say . . .
> pwd
~/my-project/

# If dir-c has dir-c/nested/foo in it
> ls
config.json  dir-a  dir-b  dir-c  other  files

# Fuzzy search for "foo" and pushd to it
> fj foo

> pwd
~/my-project/dir-a/nested/foo

# popd (go back)
> fj

> pwd
~/my-project/

```

## Install

```bash
```
