## Overview

# Ansible Basics

Ansible is an open-source automation platform that is used to automate the deployment, configuration, and management of applications and infrastructure. It uses a simple, human-readable language called YAML to describe the tasks that need to be automated, and it uses SSH to execute the tasks on the target systems.

**Here are some basics of Ansible**:

1. **Ansible playbook**: An ansible playbook is a YAML file that defines the tasks that need to be automated. The playbook is organized into a series of tasks that are executed in a specific order, and it can include variables, loops, and conditional statements to provide flexibility and customization.

1. **Ansible inventory**: An ansible inventory is a file that defines the target systems that the playbook will be executed on. The inventory can include a list of hostnames or IP addresses, as well as group names and variables that can be used to classify and identify the systems.

1. **Ansible modules**: Ansible modules are pre-written pieces of code that are used to perform specific tasks on the target systems. Ansible includes a wide range of built-in modules for tasks such as installing packages, managing users, and managing files.

1. **Ansible roles**: Ansible roles are reusable collections of tasks and variables that are used to automate the deployment and configuration of specific applications or services. Roles can be shared and reused across different playbooks, and they can be stored in a central repository for easy access and management.

1. **Ansible Hosts**: Ansible hosts field specifies the target systems that the playbook will be executed on. The hosts field can contain a list of hostnames or IP addresses, as well as group names and variables that can be used to classify and identify the systems.

Example:
```
```
