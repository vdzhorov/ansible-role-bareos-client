# Ansible role Bareos client

Ansible role for installing and configuring Bareos client on a target host.

## Getting Started

Check out my [Bareos director role](https://github.com/vdzhorov/ansible-role-bareos-director) for more complete documentation.

### Configuring the client

Client configuration is done on two mashines: the director and the client. The director holds configuration for pools, volumes, clients, shedules and etc. The client only has configuration related to establishing connection with the director. In order to add a new client, you will need to:

* Have the client present in your inventoy file
* Have the client present in the *bareos_clients* var. This var can be either a host var or a group var, depending on your preference.

## Built With

 [Ansible 2.8](https://docs.ansible.com/ansible/2.8/index.html) - Ansible 2.8

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company
* **Delta.BG**

## License

This project is licensed under the MIT License.
