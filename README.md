# openra-ansible
## General
a pretty simple playbook to run an openra-server in docker, thanks to [rmoriz' openra docker build](https://github.com/rmoriz/openra-dockerfile). Just change the vars and have fun.

## Usage

```
git clone https://github.com/Lyra1337/openra-ansible.git
cd openra-ansible
```
now change the host in the inventory to the host you'd like to use:
```
nano inventory/default.yml
```
make sure to have your pubkey on the root user of the just configured host!

to run the ansible script use:
```
ansible-playbook site.yml
```

## Contributing
please contribute.

## Donating
pls send doge.
