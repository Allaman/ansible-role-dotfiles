# ansible-role-dotfiles

This role consists of two parts:

1. Run my [bootstrap](https://github.com/Allaman/dots/blob/main/bootstrap.sh) script from my [dots](https://github.com/allaman/dots)
2. Download various shell plugins/tools

   - fzf
   - zsh-autosuggestions
   - fast-syntax-highlightning
   - zsh-completions
   - Tmux tpm

## Test

Run `molecule test` for testing this role via Docker

## Requirements

## Role Variables

## Dependencies

## Example Playbook

```
---
- name: Playbook
  hosts: localhost
  connection: local
  roles:
    - ansible-role-dotfiles
```

## License

MIT
