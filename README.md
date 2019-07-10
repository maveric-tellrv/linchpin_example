LinchPin Openstack Pin file example

sudo yum install python-pip python-virtualenv libffi-devel \
openssl-devel libyaml-devel gmp-devel libselinux-python make \
gcc redhat-rpm-config libxml2-python libxslt-python git

pip install linchpin

cd openstack

linchpin -vvv up
