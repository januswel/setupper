setup-playbook
===

Getting Started
---

0. Xcode
1. HomeBrew
2. Ansible

### Xcode

Install from App Store. Then type following command to agree license.

```sh
sudo xcodebuild -license
```

Install command line tools.

```sh
xcode-select --install
```

### Homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)
```

### Ansible

```sh
sudo easy_install pip
sudo pip install ansible
```

Run playbook
---

```sh
ansible-playbook -vv ./playbook.yml
```

References
---

http://t-wada.hatenablog.jp/entry/mac-provisioning-by-ansible
