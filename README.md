*     LinchPin Openstack Pinfile example

      sudo yum install python-pip python-virtualenv libffi-devel \
      openssl-devel libyaml-devel gmp-devel libselinux-python make \
      gcc redhat-rpm-config libxml2-python libxslt-python git

*     pip install linchpin

*     cd openstack

*     linchpin -vvv up


This will create inventories inside "inventories"
      
 
      ```
      [lts]
      10.0.0.46 hostname=10.0.0.46

      [sut]
      10.0.0.45 hostname=10.0.0.45

      [all]
      10.0.0.45 hostname=10.0.0.45
      10.0.0.46 hostname=10.0.0.46
      ```
