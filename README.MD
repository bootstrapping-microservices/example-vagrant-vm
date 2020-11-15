# Example Vagrant VM

An example Vagrant virtual machine setup with Docker and Terraform installed.

This example accompanies the book [Bootstrapping Microservices](http://bit.ly/2o0aDsP). It's a practical and project based guide that takes you from a single microservice on your dev PC to a complete microservices application deployed to a production Kubenetes cluster.

## Prereqs

To try out this example you need [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html) installed.

## Booting the example VM

Clone this repo:

```bash
git clone https://github.com/bootstrapping-microservices/example-vagrant-vm
```

Change directory into the local repo:

```bash
cd example-vagrant-vm
```

Boot the VM using Vagrant:

```bash
vagrant up
```

Now connect a command line shell to the VM:

```bash
vagrant ssh
```

You can now invoke commands at the shell to execute them in the VM.