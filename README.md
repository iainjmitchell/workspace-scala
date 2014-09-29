###Requires:

* [Vagrant](https://www.vagrantup.com/)
* Vagrant omnibus plugin
```terminal
sudo vagrant plugin install vagrant-omnibus
```
which will require on OSX...
```terminal
xcode-select --install
```

###To setup
Run the following from inside the checked out folder
```terminal
vagrant up 
```

The workspace folder is shared with the VM in /usr/local/workspace
