# Git -- GPG

Very base setup of GPG. It installs GPG, app for entering pin and Git. Motivation for creating this role is to prepare system for [signing Git commits](https://help.github.com/articles/signing-commits-using-gpg/). I based this role on stuff from [Set up Keybase.io, GPG & Git to sign commits on GitHub](https://github.com/pstadler/keybase-gpg-github). This guide was a big help and I recommend to check it at least quickly to everyone.

## Requirements

This role is installing software via [Homebrew](https://brew.sh), so installed Homebrew would be nice ;)

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
