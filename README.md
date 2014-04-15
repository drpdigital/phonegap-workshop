phonegap-workshop
=================

Learning PhoneGap


Vagrant
-------

For those that want a ‘quickstart’ a vagrant box is available with phonegap and the android sdk  pre-installed.

Sadly the box is reasonably large and totals at 2GB in size due to the size of the android SDK and all the prerequisites.

To use this you will need to have [Vagrant](http://www.vagrantup.com/) and [Virtualbox](https://www.virtualbox.org/) installed.

After those have been installed just open a commandline and navigate to this repositories directory and run:
```bash
vagrant up
# Then wait for this to complete
vagrant ssh
```
This should take you into a slightly different looking shell, this will be inside a virtual machine but will still be able to access this projects folder.

Local
-----

If you do not want to use a virtual machine and would like to have a full toolchain on your machine then here is what you need.

- [NodeJS](http://nodejs.org) (for npm)
- [Android SDK](https://developer.android.com/sdk) This is rather large when unpacked
- [Ant](https://ant.apache.org/manual/install.html) (Should be available in most package managers)

Make sure these are all installed in your path then install Phonegap via npm
```bash
npm install -g phonegap
```
The ```-g``` will install it globally so that you can run the phonegap command from anywhere on your system.
