# Ansible Role: tmux

An Ansible role that installs and configures tmux on Linux.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

    ssmtp_recipient: postmaster
    ssmtp_mailhub: mail
    ssmtp_use_tls: yes
    ssmtp_auth_username: ~
    ssmtp_auth_password: ~

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
        - { role: mjanser.tmux }

## License

MIT
