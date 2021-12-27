# Project1
For this project I set up an Azure network with a JumpBox, 2 virtual machines running metricbeat and filebeat, an ELK stack, Security Groups, and load balancing.
The jumpbox was running ansible so we could run playbooks on the VMs and SSH in to them.
Using a Docker container we ran playbooks to download metricbeat and filebeat on to the two VMs.
The ELK stack was used for the K in ELK or Kibana and getting Metricbeat and Filebeat analytics via HTTP.
The Security groups made sure that the VMs are only accesible via ssh and the ELK stack Via both SSH and HTTP.

