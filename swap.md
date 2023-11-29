# Install

`sudo swapon --show`

`free -h`

`df -h`

`sudo fallocate -l 5G /swapfile1`

`ls -lh /swapfile1`

`sudo chmod 600 /swapfile1`

`sudo mkswap /swapfile1`

`sudo swapon /swapfile1`

`echo '/swapfile1 none swap sw 0 0' | sudo tee -a /etc/fstab`

`cat /proc/sys/vm/swappiness`

`sudo sysctl vm.swappiness=10`

`cat /proc/sys/vm/vfs_cache_pressure`

`sudo sysctl vm.vfs_cache_pressure=50`