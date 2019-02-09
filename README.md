# ansible-macos  
This is the ansible playbook to use for macOS Setup.  

## Getting Started

#### Install [Homebrew](https://brew.sh/).

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Install Ansible with Homebrew.

```
$ brew install ansible
```

#### Run the playbook.

```
$ ansible-playbook -i hosts site.yml
```

## Licence

This software is released under the MIT License, see LICENSE.
