# Vagrant Cloud Foundry Locally

PCF Dev is the simplest way to get a complete Cloud Foundry on a single machine.


## Prerequires

1. Git 2.6+
2. VirtualBox 5+
3. Vagrant 1.8+

## How to Play

Clone

```
git clone https://github.com/humbertodias/vagrant-cloud-foundry-dev.git
```

Inside the folder

```
cd vagrant-cloud-foundry-dev/pcfdev-v0.15.0
```

## Running

```
vagrant up
```

## Output
```
==> default: Machine booted and ready!
Got different reports about installed GuestAdditions version:
Virtualbox on your host claims:   5.0.20 r106931
VBoxService inside the vm claims: 5.0.20
Going on, assuming VBoxService is correct...
GuestAdditions 5.0.20 running --- OK.
Got different reports about installed GuestAdditions version:
Virtualbox on your host claims:   5.0.20 r106931
VBoxService inside the vm claims: 5.0.20
Going on, assuming VBoxService is correct...
==> default: Checking for guest additions in VM...
==> default: [vagrant-hostsupdater] Checking for host entries
==> default: Configuring and enabling network interfaces...
==> default: Running provisioner: shell...
    default: Running: inline script
==> default: stdin: is not a tty
==> default: Waiting for services to start...
==> default: 0 out of 48 running
==> default: 0 out of 48 running
==> default: 0 out of 48 running
==> default: 0 out of 48 running
==> default: 0 out of 48 running
==> default: 6 out of 48 running
==> default: 48 out of 48 running
==> default: PCF Dev is now running.
==> default: To begin using PCF Dev, please run:
==> default: 	cf login -a api.local2.pcfdev.io --skip-ssl-validation
==> default: Email: admin
==> default: Password: admin
```

## Output

![Preview](doc/cf-login.png)

## References

1. PCF-Dev Doc
	
	[https://docs.pivotal.io/pcf-dev/](https://docs.pivotal.io/pcf-dev/)

2. PCF-Dev Download

	[https://network.pivotal.io/products/pcfdev](https://network.pivotal.io/products/pcfdev)