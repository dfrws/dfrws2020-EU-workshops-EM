# DFRWS EU2020 Workshop - Insights from Waves

This repository contains the materials that will be used at the **Insights from Waves** workshop of DFRWS EU 2020. The participants need to attend with a computer configured with our virtual machine. The virtual machine is configured with all the required software environments and tools. You can setup your virtual machine by taking the following steps.

## Setting up a computer for the workshop

0. You need a host computer where you can dedicate at least 4GB of RAM and 20GB of disk space for a virtual machine.

1. Install **Oracle VirtualBox** and **VirtualBox Extension Pack** on your host computer. We've tested on VirtualBox version 5.2. Link: https://www.virtualbox.org/wiki/Downloads

2. Download the **EMvidenceVM.ova** file from the following link and import it on VirtualBox. The downloadable file is about 3.4GB large. When importered into VirtualBox, it will take upto a maximum of 20GB disk space. Most probably, it will be less than that.
Link: https://drive.google.com/drive/folders/154vCmQ9EeXErynA40HhBsHqGtXVEMWP7?usp=sharing

3. Start the VM and login at the bash prompt with username **emvidence** and password **emvidence**. Once logged-in, type **startx** and press ENTER to start the graphical desktop environment.

4. We need to get the latest workshop materials that will be downloaded with the help of a shell script. On the Desktop, you can find the shell script called **update-workshop-materials.sh**. Open a terminal at the Desktop and type the following command to run that shell script. It will download the latest version of workshop materials from this Github repository to the desktop.

     ```./update-workshop-materials.sh```

Now you are good to go! If you have any queries about the above steps, please feel free to contact me through the following email address: asanka[dot]sayakkara[at]ucdconnect[dot]ie.
