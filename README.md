# Ansible MacOS Setup

This Playbook installs and configurates settings for my MacOS that I use.
There are 2 roles, configuration-common is tasks for homebrew install and upate
mac-applications role is for install particular applications. you can change main.yml file to customizing your preferences 

## Roles
- configuration : install and update homebrew, setup system preference(ex, Clock display)
- mac-application : install applications with brew, brew_cask, download oh-my-zsh and theme

## Requirement
- pip
- ansible
- Xcode

## Installation
1. Ensure install pip
```
$ sudo easy_install pip
```
2. Ensure Install ansible
```
$ sudo pip install ansible
```
3. Ensure Install Xcode
```
$ xcode-select --install
```
4. Clone repository
```
$ git clone https://github.com/whoisxx/ansible-MacOS-setup
```

## Play
```
$ ansible-playbook playbook.yml
```

