# vg-mnist

Step by step report on how to get the final output

•	Structure 
1. [folder] vg-mnist
   1. [file] Vagrantfile
   2. [folder] pytorch-cli
      1. [file] Dockerfile
      2. [file] Script to build docker image
      3. [folder] pytorch-mnist

•	Process

1.	Cd /vg-mnist
2.	Vagrant up the VM, vagrant ssh
3.	cd /vagrant
4.	Cd pytorch-cli
5.	Run the script, or just enter: docker build -t pytorch-mnist., docker run pytorch-mnist
6.	Get the final result

