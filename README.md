# AllCom Alpine Setup

Install Alpine base packages

## Requirements

It should work on any latest alpine distribution

## Role Variables

| Variable                  | Required | Default | Choices | Comments                    |
| ------------------------- | -------- | ------- | ------- | --------------------------- |
| allcom_alpine\_\_packages | no       |         |         | list of packages to install |

## Example Playbook

    - hosts: alpine_servers
      roles:
        - role: eliseuvideira.allcom_alpine
          allcom_alpine__packages:
            - bash
            - curl
            - docker
            - git
            - make
            - rsync
            - sudo
            - tmux
            - vim
            - zsh

## License

MIT
