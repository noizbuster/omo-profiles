## Profiles
* normal : gpt + 일부 fast
* fast : gpt 전체 fast + spark
* budget : gpt 전체 normal
* glm5only : glm5.1 + glm-5-turbo

## Guide

아래 alias 를 ~/.zsh_aliases 혹은 ~/.zshrc 에 추가

```bash
alias ocb='OPENCODE_CONFIG_DIR=$HOME/.config/opencode/omo-profiles/budget opencode'
alias ocg='OPENCODE_CONFIG_DIR=$HOME/.config/opencode/omo-profiles/glm5only opencode'
alias ocf='OPENCODE_CONFIG_DIR=$HOME/.config/opencode/omo-profiles/fast opencode'
alias oc='OPENCODE_CONFIG_DIR=$HOME/.config/opencode/omo-profiles/normal opencode'
```
