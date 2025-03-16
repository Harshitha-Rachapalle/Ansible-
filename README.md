# Ansible-

Ansible is an open source automation tool used for configuration management, application deployment and task automation. It simplifies complex tasks, making it easier to manage and configure servers and applications.

**How ansible works?**

* Ansible is an **agentless architecture**.  It will connect through ssh keys , username and password.
* Ansible is a **push based mechanism**

  **Ansible architecture**

  **control node:** where ansible is installed and run
  
  **manage nodes:** the target systems which is managed by ansible, accessed over ssh/ win RM
  
  **Inventory:** defines manage nodes and their grouping
  
  **Modules and playbooks:** defines tasks and desired state
  
  **Roles:** A method to organize playbooks and other files into reusable and modular units

  **collections:** A distribution format for ansible content, including roles,modules and plugins
