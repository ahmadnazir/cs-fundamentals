# Setting up video call

We are using hangouts for video calls

# Setting up "Atom"

Atom is an open source text editor. It is hackable!

## Installing Atom

Download atom's .deb package file

```
sudo dpkg -i PACKAGE_FILE.deb
```

Normally, you would install packages using apt-get but sometimes it is convenient to directly install .deb files using `dpkg`.

How to find more information about commands? e.g. what if you don't know what dpkg means or does?

```
man dpkg # this stands for "show me the manual of dpkg"
```

In order to install atom for 32 bit architectures:

```
sudo add-apt-repository ppa:webupd8team/atom

# We need to add the public key since the above repository isn't recognized
# SECURITY NOTE : This is not safe since we didn't verify that the public key actually does belong to the repository that has the atom packages
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys C2518248EEA14886

sudo apt-get update
sudo apt-get install atom
```


# Checking the architecture of your machine

```
uname -a
```

# Exercise

- Try out Atom
- Read about atom
- Merge the pull request that contains this file
- Create a pull request that fixes the timing information in the previous session file

# Summary

i 2016/08/09 22:00:00 gokustan
o 2016/08/09 23:30:00 done
