
# 1. Using a basic text editor

```
gedit # gnome-edit
```

# 2. How to control processes in the terminal

```
gedit /etc/apt/sources.list
# press Ctl-z, stops the process
bg # puts the process in background and you get back control of the terminal

# OR start the process in background to begin with


gedit /etc/apt/sources.list & # starts in background
```


# 3. Check the file ownership

```
cd ~ # change directory to home directory i.e /home/YOUR_USERNAME/ i.e. /home/bilal/ 
cd   # same thing as above
```

```
ls    # list the files
ls -l # list the files in long format .. shows file owners, groups etc
```

check the owner of a file owned by root:

```
ls -l /etc/apt/sources.list # show the file in long format
```

# 4. Intro to package manager

```
# Ubuntu used apt package manager
# install a package
sudo apt-get install gksu

# remove a package
sudo apt-get remove gksu
```

when a package isn't available by default, you have to add a
repository to the sources file once the sources.list file etc, is
update, then you have to update apt-get

```
sudo apt-get update
sudo apt-get install chrome
```

# 5. Logged in as root or a normal user

when logged in as a normal user, you will always see a dollar sign '$' on the terminal:

```
bilal@goku ~$
```

when logged in as root, you will always see a hash '#' in the terminal

```
bilal@goku ~#
```

# Exercises

- Create account in github
- Read a little about git
- Read about markdown (the format of this file)
- Start using gedit instead of libre office (later we will move to vim or another advanced text editor) 
