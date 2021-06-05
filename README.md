# chezmoi-bug

This turned out not to be a bug after all, but rateher a misunderstanding on my part.

I added the `chezmoi.toml` config like this:

```sh
$ chezmoi add --template .config/chezmoi/chezmoi.toml
```

Which sorta works, but not completely.

Moving my template config to `.chezmoi.toml.tmpl` made the problem go away.
