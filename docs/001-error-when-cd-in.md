# when cd in error

~~~
This system is currently not set up to build kernel modules. Please install the gcc make perl packages from your distribution
~~~

## solution
```shell
# You probably need to install these 2 packets: virtualbox-guest-utils and virtualbox-guest-dkms
# It will require few seconds through this terminal command:

sudo apt install virtualbox-guest-utils virtualbox-guest-dkms

# Then execute again `sudo ./VBoxLinuxAdditions.run` as you did and it should work fine ;)
```


## resources
- https://askubuntu.com/questions/1140770/this-system-is-currently-not-set-up-to-build-kernel-modules-please-install-the