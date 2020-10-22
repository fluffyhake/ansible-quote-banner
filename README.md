# ansible-quote-banner-script

Hello!

This project grabs a quote of the day via a rest "get", and pushes the qute into banners on defined network devices via Ansible.

This repo requires Anisble to be installed:

Installing Ansible from PPA repository:
1 . Update your package index and install the software-properties-common package. This software will make it easier to manage this and other independent software repositories. Add the Ansible PPA and refresh your system’s package index once again.
apt install software-properties-common
apt-add-repository ppa:ansible/ansible
apt update


2 . Install the Ansible software
apt install ansible


3 . Check that the installation is successful
ansible --version
