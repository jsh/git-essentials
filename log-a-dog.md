### git lol

I use an alias that I like a lot: `git lol`

This isn't part of the Git distribution, but it's very common.
It's an example of how to define aliases.

This shows it's not there until you define it.

```
git lol
```

And this is how to define it, see it, and use it

```
git config --global alias.lol 'log --all --decorate --oneline --graph'
git config --global alias.lol
git lol
```
