# ANSIBLE ROLE JENKINS
=========
-------------------------
## Installs Jenkins for Ubuntu linux servers.
## Requirements
-------------------------
    OS: Ubuntu

## Role Variables
--------------
    --- 
    java: "openjdk-11-jdk"
    jenkins: 
      repo_URL: "https://pkg.jenkins.io/debian-stable/jenkins.io.key"

## Dependencies
------------
    None.

## Example Playbook
----------------
    ---
    - name: Install Jenkins
      hosts: linux123
      become: true 
      # gather_facts: false 
      roles:
        - role-jenkins

## License
-------
    LÊ NGỌC HIẾU

## Author Information
------------------

    This role was created in 2022 by Lê Ngọc Hiếu from Việt Nam, Devops Engineer

