# hub-snap

## Development

This snap needs to be built on Ubuntu 16.04 for some reason. A `Vagrantfile` is included in this repo. You can do the following:

```
vagrant up
vagrant ssh
sudo apt update
sudo snap install --classic snapcraft
cd /vagrant
snapcraft
```
