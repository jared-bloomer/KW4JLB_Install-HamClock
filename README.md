To install run the following commands

```BASH
git clone https://github.com/jared-bloomer/KW4JLB_Install-HamClock.git
cd KW4JLB_Install-HamClock
bash install.sh
ansible-playbook install_hamclock.yml
```

By Default this will compile and install Ham Clock using the 800x480 resolution. If you wish to change this, edit ``group_vars/all.yml`` and set the resolution to the value you want to use. Then run ``ansible-playbook install_hamclock.yml`` again.

After the installation is complete, you can run hamclock with the command ``hamclock &``


