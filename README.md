# ansible-fedora-laptop

### To use these playbooks, you'll need to install the dependency collections.
Assuming you've just cloned this repo.

    $ ansible-galaxy collection install -r ./ansible-fedora-laptop/collections/requirements.yml

### You'll then want to run the site.yml to install all packages.

    $ cd ansible-fedora-laptop 
    $ ansible-playbook ./site.yml
