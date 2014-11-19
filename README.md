## administration

  [![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Describe your role in a few paragraphs....


### Role dependencies

- `geerlingguy.ntp`

### Role variables

List of default variables available in the inventory:

```yaml
    #ubuntu
    ntpservers:
      - "ntp.ubuntu.com" 
      - "timehost"
    
    nisserver: albandri
    mailserver: smtp.gmail.com
    
    #TODO use authorized_key instead of copy-keys.yml
    #See http://brokenbad.com/better-handling-of-public-ssh-keys-using-ansible/
    base_admin_username: ubuntu # something non-root
    base_admin_keys: []
```


### Detailed usage guide

Describe how to use in more detail...


### Authors and license

`administration` role was written by:
- [Alban Andrieu](nabla.mobi) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu)
- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-administration/issues)!

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
