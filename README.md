## Mail my IP address ##

This playbook will capture the IP address(es) and mail it to the addressee, defined in the variables.

### Execute ###
Pull this repository to your local machine and enter the following command:
```sh
 $ ansible-playbook site.yml
```
- Check your mail!

## Variables
In the role-defaults you will find the variables:
- from_address
- to_address

Add your values to it.

In the group_vars you can enter the ansible-ssh and -password values, by default it is using vagrant/vagrant to be used by the deployment of a Vagrantfile.
See this project: https://github.com/NicoOosterwijk/vagrant-mail_my_ip 
