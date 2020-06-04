# proxmox_lxc_updater
Update all LXC with one simple script

Simple bash script to APT update all LXC containers which are stopped or running status

Will start stopped containers to update then shut them down in the background and move on to next container



# Usage
make executable and run

```zsh
[#]git@fachinformatiker:~> chmod +x updater.sh
[#]git@fachinformatiker:~> ./updater.sh
```
