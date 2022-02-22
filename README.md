# vagrant-getting-started
https://learn.hashicorp.com/tutorials/vagrant/getting-started-index?in=vagrant/getting-started

Prerequisites:
Install the latest version of Vagrant.
Install VirtualBox

# clone code
git clone

# spin up virtual box
vagrant up

# connect to vm in virtual box
vagrant ssh
# Note: When you vagrant ssh into your machine, you're in /home/vagrant, 
# which is a different directory from the synced /vagrant directory.

# access webpage locally
http://127.0.0.1:4567

# to share weberver across internet
# install ngork
https://ngrok.com/download
# install vagrant-share plugin
vagrant plugin install vagrant-share
# start session
vagrant share

# share the url provided in above command output
