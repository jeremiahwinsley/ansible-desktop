This playbook requires Ubuntu 18.04 Desktop.
By default it installs the dotfiles to the user `jeremiah`.

1. Install prerequisites: `apt install ansible python-apt`
2. Clone the repository: `git clone https://github.com/jeremiahwinsley/ansible-desktop.git`
3. Run the playbook: `ansible-playbook -i hosts local.yml`
4. Reboot to load the changes
