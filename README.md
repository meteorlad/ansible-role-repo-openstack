# Ansible-role-repo-openstack

Role for repo openstack

## Requirements

Tested with Ansible 1.9.5

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    openstack_repo_url: "http://mirror.centos.org/centos-{{ ansible_distribution_major_version }}/{{ ansible_distribution_version }}/cloud/$basearch/openstack-liberty/"


## Dependencies

None


## Example Playbook

    - hosts: openstack
      roles:
        - repo-openstack

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Meteor Liu](http://meteorlad.me/)

