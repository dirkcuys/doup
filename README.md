# Digital Ocean UP

Ansible script for setting up new DO instance in an instant

Follow [digital ocean instructions for setting up a new instance](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04)

Example:

    ansible-playbook -u root -i "staging-learningcircles.p2pu.org," -e "USER=admin PASSWORD=XXXXXXXXX" site.yml


# TODO
 [ ] Figure out better way of handing passwords
 [ ] create droplet - http://docs.ansible.com/ansible/digital_ocean_module.html
 [ ] store recorded facts?
 [ ] Add accepted public key root is using to user account
