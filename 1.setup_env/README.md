## Setup local volume 
```bash
sysctl -w vm.max_map_count=262144
mkdir ~/DockerData
sudo chmod -R g+rwx ~/DockerData
sudo chown 1000:1000 -R ~/DockerData
```