This playbook is meant to run on a Fedora 23 minimal installation.
You should be logged in as the account you plan to use.

1. Install prerequisites: `dnf install ansible python-dnf git`
2. Clone the repository: `git clone https://github.com/jeremiahwinsley/ansible-desktop.git`
3. Run the playbook: `ansible-playbook -i hosts local.yml`
4. Reboot to load the changes
