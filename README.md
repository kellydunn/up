```
 __  __  _____   
/\ \/\ \/\ '__`\ 
\ \ \_\ \ \ \L\ \
 \ \____/\ \ ,__/
  \/___/  \ \ \/ 
           \ \_\ 
            \/_/ 
```

#what

Provisioning scripts for my personal and work machines.  The intent of this project is to have a single `curl`-able script that could partition and provision my machines into a working state.

#usage

```
git clone git@github.com:kellydunn/up
cd up
ansible-playbook arch.yml --connection=local -i inventory.yml
```

#status

At the moment, the scripts require ansible to be installed on your system, but in future iterations, there should be scripts that could provision your machine from a LIVE CD of your linux distro of choice.