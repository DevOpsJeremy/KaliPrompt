# Kali Linux-Inspired PowerShell Prompt
This is a PowerShell console prompt inspired by Kali Linux's colorful, multiline [ZSH terminal prompt](https://www.kali.org/blog/kali-linux-2020-4-release/#zsh-shell-by-default). Thanks to [Bob](https://superuser.com/users/117590/bob) on Stack Overflow for [his answer](https://superuser.com/a/1259916).

I added a feature where if your present working directory (PWD) is a Git repository, it will run `git rev-parse --show-toplevel` to get the repo name and include it in the prompt. Feel free to leave this out if you don't need/want it.
