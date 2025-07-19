---
docType: "Chapter"
id: "Compute"
chapterTitle: "Compute"
description: ""
title: "Compute"
weight: 1
---

### **Overview**

The Compute product is for scalable, on-demand cloud servers in a privacy-minded public cloud setting to host everything from simple applications to complex architectures. Start a virtual machine (VM) in seconds, and integrate current on-premises or hybrid-cloud deployments using standard DevOps tooling, would that be Terraform, Kubernetes, Ansible, or the tools of your choice.

### **VM Creation – Essential Properties**

 - **Name** - Easier Server Identification
 - **Template** - Linux, Windows, Custom, Marketplace
 - **Zone** - Data Center Locations
 - **Instance type** - RAM, CPU Core Configurations (T-Shirt Sizes)
 - **Disk size**- Size Configurations

![image]({{< usestatic "advanced-course/user_interface1.png" >}})

### **VM Creation - Further Properties**

 - SSH Keys
 - Public IP Assignemnt
 - Private Networks
 - Security Groups
 - Anti-Affinity Groups
 - User Data

![image]({{< usestatic "advanced-course/user_interface2.png" >}})


### **EXAMPLE - create a Linux VM and install a web server**

Walking through a step-by-step example for creating a new cloud server (VM) with a web server manually:

 - Create Security-Group for HTTP and SSH access
 - Create SSH Keyfile for access
 - Start a Virtual Machine
 - Install a Web Server via SSH

### **Security Group**

Security Groups are the VMs firewall, all VMs are linked to at least one Security Group (default).

**default**

 - BLOCK all incoming traffic
 - ALLOW all outgoing traffic

![image]({{< usestatic "advanced-course/security_group1.png" >}})

![image]({{< usestatic "advanced-course/security_group2.png" >}})

**Security Group - configure a new sample-group**

![image]({{< usestatic "advanced-course/sample_group1.png" >}})

![image]({{< usestatic "advanced-course/sample_group2.png" >}})

![image]({{< usestatic "advanced-course/sample_group3.png" >}})

![image]({{< usestatic "advanced-course/sample_group_finish.png" >}})

For our example:

 - ALLOW 22 for everyone
 - ALLOW 80 for everyone


### **SSH Keys**

**How-to create an ssh key pair**

![image]({{< usestatic "advanced-course/ssh_keygen.png" >}})

**Linux and Mac**

 - Use the command line tool **ssh-keygen**

**Windows**

 - Use the program PuTTYgen (**puttygen.exe**) and export the OpenSSH public key

### **Create SSH Key - my-key**