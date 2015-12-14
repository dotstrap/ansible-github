github
=========
[![Build Status](https://travis-ci.org/mkwmms/ansible-github.svg)](https://travis-ci.org/mkwmms/ansible-github)

Install & configure: git & packages that enchance git.


Requirements
------------

OS X: [homebrew] and the latest XCode tools.

Archlinux: [pacaur]

Role Variables
--------------

See [default variables] & [variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.github }
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]


[@mkwmms]: https://github.com/mkwmms
[dotstrap]: https://github.com/mkwmms/dotstrap
[homebrew]: https://github.com/Homebrew/homebrew
[pacaur]: https://github.com/rmarquis/pacaur
[files]: files/
[default variables]: defaults/main.yml
[variables]: vars/
[zsh]: http://zsh.sourceforge.net
[fish]: http://fishshell.com/
