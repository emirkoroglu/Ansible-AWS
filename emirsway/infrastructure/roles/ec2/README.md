Role Name
=========
- Create a 5 EC2 instance by ec2.yaml playbook which will run the role for you. If you want to edit the details check the /roles.
Instance details;
      key_name: laptop
      instance_type: t2.micro
      image: ami-074cce78125f09d61
      wait: yes
      count: 5
      region: us-east-2

- Install a Wordpress and dependencies by running wordpress.yaml on a Ubuntu.

- Create a IAM user and DevOps group by running user_group.yaml

Requirements
------------

Support Ansible 1.2 and above.

Ubuntu for Wordpress.


Role Variables
--------------

Wordpress;
In roles/wordpress/defaults/main.yml , you have to put your database name and mysql account and password for wordpress.


More about my work check below
-------
https://github.com/emirsway
https://galaxy.ansible.com/emirsway


Contact
-------
emirmails@gmail.com


License
-------
Check License.md