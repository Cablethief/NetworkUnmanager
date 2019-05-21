
# NetworkUnmanager

Within NetworkManager it is possible to unmanage an interface, this is very useful if you would like to continue using Network manager when using wireless tools for a specific interface. 

[Create_ap](https://github.com/oblique/create_ap) and by extension [Berate_ap](https://github.com/sensepost/berate_ap) do this automatically for you on whichever interface you are using. Sometimes you would like to just toggle the management of a specific interface for other tools.

Using the code from Create_ap this is a small script to just toggle the managed and unmanaged status of a interface for Wireless testing. 

# Usage 

```
sudo unmanage_interface -i <Interface>
```

# Installation

Add `unmanage_interface` to your path in your .rc file

```
export PATH=/path/to/unmanage_interface:$PATH
```

or create a symlink to your bin directory

```
cd /usr/local/bin
ln -s /path/to/unmanage_interface unmanage_interface
```
