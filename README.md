# Chef Cookbook Development Set Up 
This repository simplifies the provisioning of a Chef Cookbook development environment.

The [init.bat](init.bat) script uses [Chocolatey](https://chocolatey.org/) to install the [Chef Development Kit](https://downloads.chef.io/chef-dk/) this contains:

* A chef command line tool - to streamline the Chef worflow
* The well-known cookbook dependency manager Berkshelf
* The Test Kitchen integration testing framework
* ChefSpec, which makes unit testing cookbooks a breeze
* Foodcritic, a linting tool for doing static code analysis on cookbooks
* Other Chef tools: Chef Client, Knife, Ohai and Chef Zero
