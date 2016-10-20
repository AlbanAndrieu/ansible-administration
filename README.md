## [![Nabla](https://debops.org/images/debops-small.png)](https://github.com/AlbanAndrieu) alban_andrieu_administration

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)
[![Gittip](http://img.shields.io/gittip/alban.andrieu.svg)](https://www.gittip.com/alban.andrieu/)
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=AlbanAndrieu&url=https://github.com/alban.andrieu/ansible-phpvirtualbox&title=Ansible Role: PhpVirtualbox&language=&tags=github&category=software)

Describe your role in a few paragraphs....


### Role dependencies

- `alban.andrieu.common`
### Installation

This role requires at least Ansible `v1.6.3`. To install it, run:

Using `ansible-galaxy`:
```shell
$ ansible-galaxy install alban.andrieu.administration
```

Using `arm` ([Ansible Role Manager](https://github.com/mirskytech/ansible-role-manager/)):
```shell
$ arm install alban.andrieu.administration
```

Using `git`:
```shell
$ git clone https://github.com/alban.andrieu/ansible-eclipse.git
```

### Documentation

More information about `alban.andrieu.administration` can be found in the
[official alban.andrieu.administration documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-administration/docs/).


### Role variables

List of default variables available in the inventory:

```YAML
#ubuntu
ntpservers:
  - "ntp.ubuntu.com"
  - "timehost"

nisserver: albandri
mailserver: smtp.gmail.com

apt_install_multiverse_repositories: yes  # Install some repositories (see list bellow)
apt_multiverse_repositories: ["http://us.archive.ubuntu.com/ubuntu/"]          # List of sources which be added

root_ssh_authorized_keys_enabled: yes
root_ssh_authorized_keys_fingerprints:
# Alban Andrieu
 - "ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAAIEAio3SOQ9yeK6QfKqSFNKyTasuzjStxWevG1Vz1wgJIxPF+KB0XoMAPD081J+Bzj2LCDRSWisNv2L4xv2jbFxW/Pl7NEakoX47eNx3U+Dxaf+szeWBTryYcDUGkduLV7G8Qncm0luIFd+HDIe/Qir1E2f56Qu2uuBNE6Tz5TFt1vc= Alban"

root_home: "/root"
root_user: "root"
root_group: "root"
```


### Detailed usage guide

Describe how to use in more detail...


### Authors and license

`alban_andrieu_administration` role was written by:

- [Alban Andrieu](nabla.mobi) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu)

- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

Copyright (c) 2016 [Alban Andrieu](https://alban-andrieu.com/)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-administration/issues)!

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

***

This role is part of the [Nabla](https://github.com/AlbanAndrieu) project.
README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
