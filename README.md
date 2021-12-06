MLflow server for EPU
=====================

### Deploy

Just run ``docker-compose up -d`` in the VM that the MLflow server will be deployed.

A Postgres database (parameter logging) and a minIO server (model store) are also automatically deployed. 

### Configure accessibility within EPU VMs.

See [here](https://medium.com/swlh/how-to-whitelist-ip-addresses-to-access-desired-docker-containers-5f6c8fcfa7f6) for how to deploy docker on EPU VMs and opening ports to the public:

Alternatively check file at root: How_to_Whitelist_IP_Addresses_to_Access_Desired_Docker_Containers.pdf

Follow the procedure and only allow VPN IPs to the specific port you need to reach.

