Linux 
Visit the Chef Workstation downloads page and download the appropriate package for your distribution:

Red Hat Enterprise Linux
wget https://packages.chef.io/files/stable/chef-workstation/21.10.640/el/8/chef-workstation-21.10.640-1.el8.x86_64.rpm

Debian/Ubuntu
wget https://packages.chef.io/files/stable/chef-workstation/21.10.640/ubuntu/20.04/chef-workstation_21.10.640-1_amd64.deb


Use your distribution’s package manager to install Chef Workstation:

Red Hat Enterprise Linux:
yum localinstall chef-workstation-21.10.640-1.el8.x86_64.rpm

Debian/Ubuntu:
dpkg -i chef-workstation_21.10.640-1_amd64.deb

Verify the Installation 
To verify the installation, run:
chef -v
