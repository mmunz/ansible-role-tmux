# Ansible Role: tmux

An Ansible role that installs and configures tmux on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    tmux_powerline: yes
    tmux_mouse_mode: yes
    tmux_vi_mode: yes
    tmux_plugins:
      - "tmux-plugins/tmux-sensible"
    tmux_users:
      - vagrant

### Powerline

This role configures powerline for tmux by default. This can be disabled with setting `tmux_powerline` to `no`.

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
        - { role: mjanser.tmux }

## License

MIT
