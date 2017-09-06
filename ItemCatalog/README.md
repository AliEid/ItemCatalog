fullstack-nanodegree-vm
=============


Common code for the Relational Databases and Full Stack Fundamentals courses
----------------------------------------------------------------------------
#Build-Item-Catalog-Project
#Installation Prerequisites:

1-download Git. 
2-download Virtual Box.
3-download Vagrant.
4-and install them.
#How to Run Vagrant on your PC:

1-Open Git bash terminal:
2-Move to your directory that the vagrantfile is located by entering cd vagrant/tournament.
3-Clone the virtual machine configurations
4-Start Vagrant by entering: vagrant up

#How to Run: 
.Once all steps above are complete, you can connect to the virtual machine.

1-Log into Vagrant virtual machine:
Run vagrant ssh
2-Move to vagrant directory:
Enter cd /vagrant
3-Create the required database:
Run python database_setup.py
Run python lotsofmenus.py
4-Launch Python command line:
Run python finalproject.py
