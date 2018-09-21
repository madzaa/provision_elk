# Provision a VM for running an ELK stack

## Instructions

* Open the Azure Cloud CLI
* Clone this repo 

```
git clone https://github.com/madzaa/provision_elk.git
```

* Generate an ssh key on your local machine 

```
ssh-keygen -t rsa -b 4096
```

* Add the public key to the playbook

* Run the playbook in the cloud shell by using

``` 
ansible-playbook provision-ubuntu.yaml
```

And you should be all set up
