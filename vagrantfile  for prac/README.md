we are going to create three virtual machines on which we can practice our Bash scripts, the vagrant file is placed in this folder .
You can download it from here.
First, you need to create a directory somewhere in your system.
In this directory, place the vagrant file, which is in my downloads directory.
So copying vagrantfile from downloads dir to my bash scripts dir, where I've created in d drive. Let's get into that dir.
Let's open this Vagrantfile
I'm using vim in gitbash, if you want, you can use notepad plus plus.
So there are VMs in this, script box, web01 and web02 All these three machines are using the same box, CentOS seven, and they have their own unique IP.
We're going to write all our scripts in script box, as you would have already guessed that. In first
part we will just write scripts on script box, then we will also push scripts to web01/02
We just need this one vm.
So let's bring it up.
I'm going to use vagrant up script box.
If you see a vagrant up, all three VMs will come up, but for now, we just need script box.
My VM is up.I'm going to log into it.
OK, first thing, we will set the hostname, So we will open the file /etc/hostname file and we will give
name as script box.Run the hostname, command.And now let's log out and a logging.
OK, now you see the host name is script box likewise, we will do it for the other VMs also later, which
shows in the prompt so you can understand where you are currently connected to.
So we will do sudo -i I we are going to write all our script with the root user.
