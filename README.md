ansible-github
==============
[![Build Status](https://travis-ci.org/dotstrap/ansible-github.svg)](https://travis-ci.org/dotstrap/ansible-github)

Install & configure git & packages that enchance git.

Installation
------------

```
ansible-galaxy install dotstrap.github
```

Requirements
------------

OS X: [homebrew] and the latest Xcode tools.

Archlinux: [yaourt] package manager.

Role Variables
--------------

See [default variables] & [variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: dotstrap.github
```

License
-------

MIT

Author Information
------------------

[@mwilliammyers]


[@mwilliammyers]: https://github.com/mwilliammyers
[aura]: https://github.com/aurapm/aura
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[pacaur]: https://github.com/rmarquis/pacaur
[variables]: vars/
[yaourt]: https://github.com/archlinuxfr/yaourt
[zsh]: http://zsh.sourceforge.net
