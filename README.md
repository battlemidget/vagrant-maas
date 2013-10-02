vagrant-maas
============

Quickly get up and running with MAAS

# Pre-reqs

Needs [ansible][1] installed

# Install

```
% git clone git://github.com:battlemidget/vagrant-maas.git
% cd vagrant-maas
% vagrant plugin install vagrant-lxc
% vagrant box add precise64 ..needs location..
% vagrant up --provider=lxc
```

# Running

```
% vagrant provision
```

 [1]: http://ansibleworks.com/docs/gettingstarted.html#ubuntu-and-debian
