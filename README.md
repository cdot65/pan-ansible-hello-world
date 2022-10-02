# PAN Ansible "Hello, World!"

[![N|Solid](./images/paloaltonetworks_logo.png)](https://www.paloaltonetworks.com/)

## Overview

The goal of this repository is to provide a simple "Hello World!" example of using Ansible with Palo Alto Networks products.

All files related to Ansible are stored within the [ansible](./ansible) directory at the root of this repository.

## 🚀 Executing the playbook

After [ensuring that your environment is setup properly](./docs/environment.md), change into the `ansible` directory and execute the playbook with the following command:

```sh
ansible-playbook panos.yaml
```

## 📋 Ansible version compatibility

This module has been tested back to Ansible version 2.9

## ⚙️ How it works

A quick guide on what is happening with this playbook will be [posted here](./docs/howitworks.md)
