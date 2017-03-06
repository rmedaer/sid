# Software & Infrastructure Deployment

SID stands for Software & Infrastructure Deployment.
This project was born at [Escaux](http://escaux.com/) in 2016.
Its purpose is to deploy customers infrastructures and configure their softwares.
One of main features is to add release management in top of existing automation
tools such as Ansible, Puppet, Stackstorm...

This repository contains documentation and tools to develop and build whole SID project.

## Contribute on projects

A list of working projects are available in myrepo config (`.mrconfig`).
Please clone this repository and add it in your trusted configurations.

```sh
git clone -b master git@github.com:rmedaer/sid
cd sid
echo "$PWD/.mrconfig" >> ~/.mrtrust
```

Then checkout one of projects or more:

```sh
# Checkout libjwt debian packaging and build it
mr checkout debian/libjwt
mr build debian/libjwt

# Checkout all projects
mr checkout
```

You should have build dependencies between projects. Thus you cannot `mr build`
all projects at once while the dependencies are not defined.

## Soon ...

You should find more details about this project in couple of weeks.
However if you still want to challenge ideas or discuss about it, be my guest !

RM.
