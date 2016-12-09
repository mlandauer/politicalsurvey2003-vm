# Political Survey 2003 - code archeology

This creates a virtual machine (using Vagrant) to run what is currently hosted
at http://politics.beasts.org/. This is a political survey created in 2003
by Chris Lightfoot. It uses the answers of real people to a wide-ranging
set of political questions to figure out what the real dividing lines of
politics are and what we find is that it is not a simple left-right divide.

## Requirements

* Virtual Box
* Vagrant
* Ansible

To get everything up and running

``
$ vagrant up
``

If this is the first time, that command will get the virtual machine up and running and do the provisioning. Please be patient as this will take **quite a long time**.

When it's all done point your browser at

``
http://localhost:8000
``

This should be enough to be able to complete the survey and see how your results compare to everyone else.

There are a bunch of scripts that do a bunch of different analysis on the data. I haven't yet picked apart how these work and how they need to be used. This is definitely on the list of things to do.

Enjoy!
