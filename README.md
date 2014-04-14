phonegap-workshop
=================

Learning PhoneGap


Vagrant
-------

For those that want a ‘quickstart’ a vagrant box is available with phonegap and the android sdk  pre-installed.

Sadly the box is reasonably large due tot he size of the android SDK and all the prerequisites.

To use this you will need to have [Vagrant](http://www.vagrantup.com/) and [Virtualbox](https://www.virtualbox.org/) installed.

After those have been installed just open a commandline and navigate to this repositories directory and run:
```bash
vagrant up
# Then wait for this to complete
vagrant ssh
```
This should take you into a slightly different looking shell, this will be inside a virtual machine but will still be able to access this projects folder.

