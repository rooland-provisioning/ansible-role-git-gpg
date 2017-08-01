# Git -- GPG

Very base setup of GPG. It installs GPG, app for entering pin and Git. Motivation for creating this role is to prepare system for [signing Git commits](https://help.github.com/articles/signing-commits-using-gpg/). I based this role on stuff from [Set up Keybase.io, GPG & Git to sign commits on GitHub](https://github.com/pstadler/keybase-gpg-github). This guide was a big help and I recommend to check it at least quickly to everyone.

## Requirements

This role is installing software via [Homebrew](https://brew.sh), so installed Homebrew would be nice ;)

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

### Defaults

|             Name          |  Type  |   Description                                                                                                       |
|---------------------------|--------|---------------------------------------------------------------------------------------------------------------------|
| git_gpg.git.signing_key   | String | Default signing key for Git. See [user.signingKey](https://git-scm.com/docs/git-config#git-config-usersigningKey).  |

### Variables

|             Name          |  Type  |   Description                                                                                                       |
|---------------------------|--------|---------------------------------------------------------------------------------------------------------------------|
|                           | String |                                                                                                                     |

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - hosts: localhost
      roles:
        - role: git-gpg
          tags:
            - git
            - gpg

## License

MIT

## Author Information

### Mailo Světel

- Usually idling on Freenode as lipoqil
- http://mailo.svetel.cz
