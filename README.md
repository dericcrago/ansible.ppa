# Ansible PPA Testing

## Usage

### End User

#### Latest Stable Version

```bash
sudo add-apt-repository ppa:deric.crago/ansible
sudo apt-get update
sudo apt-get install ansible
```

#### Beta Version

```bash
sudo add-apt-repository ppa:deric.crago/ansible-base
sudo add-apt-repository ppa:deric.crago/ansible-beta
sudo apt-get update
sudo apt-get install ansible
```

### Maintainer

#### New Version

Bump the appropriate variables in the github workflow(s) and submit a PR.
