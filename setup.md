#Installing Git
Run the following command in your terminal.

```bash
sudo apt install git
```

It will ask you y/n to install, select y(es).

After installing you will need to setup your private public key
for github.

#Creating SSH key
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

#Copying ssh key
By default cat ~/.ssh/id_rsa.pub will list the contents of your
public key. Copy this key and paste that key in your ssh keys on
github in your profile settings.

Note: This public key can be used for things other than github
like ssh'ing into other servers without having to use a password
or pem file.


#Installing Atom
https://flight-manual.atom.io/getting-started/sections/installing-atom/
