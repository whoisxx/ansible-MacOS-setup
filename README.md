This is Easy install setting on MacOS application that I use.
There are 2 roles on this ansible, configuration-common is task lists for homebrew install and upate
mac-applications role is for install particular applications. you can change main.yml file to customizing your preferences 

# Requirement
- pip
- ansible
- Xcode

# Installation
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

# Play
```
$ ansible-playbook playbook.yml
```

