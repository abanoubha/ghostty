# ghostty config

my simple config for ghostty terminal

> [!NOTE]
> This config is opinionated and created by Abanoub Hanna, for Abanoub Hanna. You can use it as you like.

## content of my ghostty config

set fish shell as my shell of choice:

```plain
command = /bin/fish --login --interactive
```

and enable shell integration features:

```plain
shell-integration = detect
shell-integration-features = cursor,sudo,title
```

Change the theme:
I like dark background with text with great contrast and non-glowy colors, so I chose `Builtin Tango Dark` after consulting `ghostty +list-themes`

```plain
theme = Builtin Tango Dark
```

## my other config

- ghostty config (this repo)
- [nvim config](https://github.com/abanoubha/nvim)
- [vim config](https://github.com/abanoubha/vim)
- fish shell config (currently private)

