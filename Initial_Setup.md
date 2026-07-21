# Ubuntu Server Setup

This documents initial setup of Ubuntu Server in Virtualbox. A static IP is set and connectivity is confirmed before a snapshot is taken.

## Setting Static IP Address
After installing Ubuntu Server in Virtualbox and logging in, I first run 'ip a' to check my interface names.

![ip a output](screenshots/ip_a.png)


Next I want to set a static IP address on my Host-Only adapter, so that I can always reach it. To accomplish this, I go into network config, and find it looking like this.

![network config](screenshots/network_config_before.png)

I edit the file to assign enp0s8 a static 192.168.56.20/24 address.

![network config after](screenshots/network_config_after.png)

## Confirming connectivity

I run 'ip a' again to confirm the new static IP.

![ip a after](screenshots/ip_a_after.png)

Next I ping google to confirm connectivity.

![ping](screenshots/successful_ping.png)

Lastly I test SSH from my Windows host OS.

![SSH](screenshots/SSH_connection.png)

Having confirmed connectivity, I take a snapshot in Virtualbox so that I can return to this base setup as needed.

![Static IP Snapshot](screenshots/StaticIP_Snapshot.png)
