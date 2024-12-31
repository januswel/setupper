# setup-playbook

## Getting Started

### Homebrew

https://brew.sh

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Xcodes

Install via [xcodes](https://github.com/XcodesOrg/xcodes).

```sh
brew install --cask xcodes
xcodes install --latest
```

Then type following command to agree license.

```sh
sudo xcodebuild -license
```

Run "Software Update" in System Settings.

### pip

https://pip.pypa.io/en/stable/installation/

```sh
python3 -m ensurepip --upgrade
```

### Ansible

https://docs.ansible.com/ansible/2.9_ja/installation_guide/intro_installation.html#from-pip

```sh
pip3 install --user ansible
```

## Run playbook

```sh
ansible-playbook -vv ./playbook.yml
```

## References

http://t-wada.hatenablog.jp/entry/mac-provisioning-by-ansible
