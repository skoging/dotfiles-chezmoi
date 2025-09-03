# github.com/skoging/dotfiles-chezmoi

Tore Hammervolls's dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

Install them with:

```console
$ chezmoi init skoging/dotfiles-chezmoi
```

Personal secrets are stored in [1Password](https://1password.com) and you'll
need the [1Password CLI](https://developer.1password.com/docs/cli/) installed.
Login to 1Password with:

```console
$ eval $(op signin)
```
