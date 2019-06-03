# Ansible for earthworm

Ansible playbook for deploying an earthworm earthworm. It will leave the system
in running an earthworm instance in a byobu terminal of user earthworm. The user
password is: ewpassword

This can be configured in the file:

    /group_vars/earthworm

## Edits for accessing the machine:

In the hosts file add your hosts under the [earthworm] group:

    [earthworm]
    #ec2-18-207-222-232.compute-1.amazonaws.com

In the EW\_FULL\_SYS.yml change the remote user to a user with root rights:

    remote_user: centos

## Editing your earthworm install:

You can change your earthworm install variables in the following file:

    /group_vars/earthworm

## Editing your earthworm configuraton.

Upload it to a git repository and change it in:

    /group_vars/earthworm

