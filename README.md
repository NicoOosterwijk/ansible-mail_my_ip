# Ansible Role: Mail my IP address

This playbook will capture the IP address(es) and mail it to the addressee, defined in the variables.

## Variables
In the defaults you will find the variables:

    from_address: whoever@host.com
    to_address: to_my_address@mailhost.com

change this to your required values.

## Dependencies

None.


## Example Playbook

    - hosts: centos
      become: true
    
      vars:
        from_address: whoever@host.com
        to_address: to_my_address@mailhost.com
    
      roles:
        - nicooosterwijk.ansible_mail_my_ip

## License

BSD

## Author
This role was created by [Nico Oosterwijk](mailto:nico@digitalinfo.nl)
