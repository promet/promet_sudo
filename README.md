promet_sudo cookbook
------------------------

This cookbook extends the contrib Opscode Sudo Cookbook

Requirements
------------
* [vagrant](http://downloads.vagrantup.com/) >= 1.2.0
* [berkshelf](http://berkshelf.com/) >= 2.0.0
* [vagrant-berkshelf plugin](https://github.com/RiotGames/vagrant-berkshelf) >= 1.3.3

Usage
-----

In your Vagrantfile, customize the contrib attributes.

[[https://github.com/opscode-cookbooks/sudo]]

Attributes
----------

No additional attributes yet.

Recipes
-------

dev - creates a sudoers.d config file named 'dev' to jail a group to specific commands.

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
License: None.  Do as you wish.
Authors: gregpalmier
