# rhel

This Ansible Network role provides a set of platform dependent functions that
are designed to work with RHEL/CentOS machines.

## Requirements

* Ansible 2.7 or later
* Ansible Network Engine Role 2.6.0 or later

## Functions

This section provides a list of the availabe functions that are including
in this role.  Any of the provided functions can be implemented in Ansible
playbooks to perform automation activities on RHEL/CentOS machines.

Please see the documentation link for each function for details on how to use
the function in an Ansible playbook.

### Cloud VPN
* cloud_vpn/configure_vpn_initiator [[source]](https://github.com/ansible-network/rhel/blob/devel/tasks/cloud_vpn/configure_vpn_initiator.yaml) [[docs]](https://github.com/ansible-network/rhel/blob/devel/docs/cloud_vpn/configure_vpn_initiator.md)
* cloud_vpn/configure_routing_initiator [[source]](https://github.com/ansible-network/rhel/blob/devel/tasks/cloud_vpn/configure_routing_initiator.yaml) [[docs]](https://github.com/ansible-network/rhel/blob/devel/docs/cloud_vpn/configure_routing_initiator.md)
* cloud_vpn/configure_vpn_responder [[source]](https://github.com/ansible-network/rhel/blob/devel/tasks/cloud_vpn/configure_vpn_responder.yaml) [[docs]](https://github.com/ansible-network/rhel/blob/devel/docs/cloud_vpn/configure_vpn_responder.md)
* cloud_vpn/configure_routing_responder [[source]](https://github.com/ansible-network/rhel/blob/devel/tasks/cloud_vpn/configure_routing_responder.yaml) [[docs]](https://github.com/ansible-network/rhel/blob/devel/docs/cloud_vpn/configure_routing_responder.md)

## License

GPLv3

## Author Information

Ansible Network Community
