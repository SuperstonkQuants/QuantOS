# GETTING STARTED WITH QUANTOS

## What it is

A Debian based Operating System for use in a Virtual Machine for Quant analysis and stonks.

It aims to standardize tools and data sources among our group, making sure our results are reproducable and our methods transparent.

Hopefully it makes getting started and following along easier, please don't be afraid to offer suggestions or ask for help.

### List of included software of note:
	Python3
	Firefox
	VSCodium
	Xcas
	R & RStudio
	JMol
	TeXdoctk
	Scilab

## What you need

The ISO: https://storage.googleapis.com/quantos/QuantOS.iso

A Virtual Machine:

	* [Default choice - VirtualBox (Windows, MacOS, most Linux)](https://www.virtualbox.org/)
	* [If you have Win10 Enterprise, Pro or Education - Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)
	* [KVM](https://www.linux-kvm.org/page/Main_Page) / [QEMU](https://www.qemu.org/) (Linux)
	* [Parallels - (paid, MacOS)](https://www.parallels.com/)
	* [VMWare Workstation (paid, all platforms)](https://www.vmware.com/products/workstation-pro.html)

## Setup

1. Install your virtual machine manager of choice.

2. Create a new Virtual Machine.

3. Choose QuantOS.iso as the installation source

4. Choose Debian Linux as the Operating System.

	You can configure how much RAM, CPU, and storage the machine has. 
	You probably want to give it at least 4GB of RAM, and two cores.
	You will be asked to create a virtual hard drive for the virtual machine, the file will expand to the max size given as it is used. 
		The base installation only takes around 11GB. 
		Filling the database takes <???>

6. Login with `deb : quants`.

Right now it's just a fancy toolbox, let us know what tools aren't there.
You can turn on and off the VM just like any other program, or set it to run in the background as you access it from the host as if it were another computer on you network.

## FAQ



## Roadmap

- [ ] Scripts to automatically populate the database at boot from various pulbic sources.

- [ ] Installer to automagically get the iso & VM set up.

- [ ] VM template for standard / faster / easier setup.

- [ ] Docker images hosting local web services.

- [ ] Script for building the .iso, so we can collaborate easier & distribute/automate the build process.
