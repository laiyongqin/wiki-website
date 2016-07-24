---
layout: post
title: Use Typora from Shell or Cmd
author: typora.io
category: how-to
tags: [dev, shell]
typora-root-url: ../../
---

## macOS

You could use `open -a typora xxx.md` to open target markdown in Typora. If Typora is your default editor for `.md` file, when `open xxx.md` would be enough.

You could also add 

```shell
alias typora="open -a typora"
```

in your `.bash_profile` or other configuration file, then you would be able to do `typora xxx.md`  to open the markdown file from shell/terminal directly.

## Windows

If Typora is set as the default markdown editor, then in cmd.exe, input `.md` file path directly would open target markdown file. For example: `./example.md`.

You would also add `{typora-insatlled-folder}/bin/typora.exe` into system Path, tehn you could be able to use `typora xxx.md` to open markdown file in Typora from command line. Usually, `{typora-insatlled-folder}` is `C:\Program Files (x86)\Typora`.