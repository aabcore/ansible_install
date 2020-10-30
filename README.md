### First Time Setup

You will need
    - a `hosts` file with one group called `[servers]` and the address(es) to the machine(s) you want to start the simulation on

### Command Line

- Run playbook against servers in hosts file
    - `ansible-playbook simulation.yml -i hosts --ask-pass -v`