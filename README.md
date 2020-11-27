# kube-zsh-theme
An ohmyzsh theme, intended to work with Kubernetes kubectl context. This theme adapts your console to the MacOS.

You can find this theme in the official <a href="https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal">**Github Wiki**</a> of Oh My ZSH.
- Tested on MacOS

## Features
- Shows current time
- Shows current kubectl context
- Shows current dir
- Shows current Git branch
- Shows arrow to differenciate input vs prompt
- Users different colors for readibility

## Installation
1. Write in your terminal `git clone https://github.com/tigerjz32/kube-zsh-theme.git/ $ZSH_CUSTOM/themes/kube-zsh-theme`
1. Open your `.zshrc`
1. Change your `ZSH_THEME` to `kube-zsh-theme/kube-zsh-theme`

## Format
`[CURRENT_TIME][CURRENT_KUBECTL_CONTEXT][CURRENT_DIR][GIT_PRMOPT_INFO]➭$`
