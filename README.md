# **Ansible + LXD: Modern Replacement for Vagrant/VirtualBox Workflows**

This repository demonstrates how to use **Ansible** with **LXD containers** as a lightweight, fast, and modern alternative to traditional **Vagrant/VirtualBox** workflows for local development and automation testing.

### Features:

* 🔧 Uses a custom `lxd_manage` Ansible role to provision and configure LXC containers.
* 🔐 Implements SSH **certificate-based authentication** for secure, scalable access to both containers and virtual machines.
* 🧪 Replaces heavyweight VM workflows with a more efficient, container-based approach.
* 🪄 Ideal for testing infrastructure automation, developing roles/playbooks, or running ephemeral environments.

### Use Cases:

* Local infrastructure-as-code development without VirtualBox overhead.
* Automated setup of isolated container environments via Ansible.
* Easily portable and reproducible testing environments for CI/CD or dev work.
