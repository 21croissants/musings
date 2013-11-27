http://getgitorious.com/documentation/developer-guide.html#sec-1-1-2 is not up to date so here are some notes to set up a Development environment to contribute to [Gitorious]( https://gitorious.org ) 

- Register on https://gitorious.org and configure
- Clone repo on gitorious and `git clone` it on your machine
- `cd my-gitorious-clone`
- (optional) Setup vagrant, dowload latest  from http://downloads.vagrantup.com/
- Setup box with `vagrant box add quantal64 https://github.com/downloads/roderik/VagrantQuantal64Box/quantal64.box`
- `vim Vagrantfile` and comment the bit on `#, :nfs => true`


