# localNetworkDown
##### Install
```
> git clone https://github.com/eBind/localNetworkDown
> cd localNetworkDown
> sudo chmod +x install.sh
> sudo bash ./install.sh
```
The program did not bring anything new to the attack process, with the exception of optimizing the work with many networks with arpspoof (dsniff package). And need root.

##### Run
```
> ./localNetworkDown.py [interface*] [router_ip*]
> # OR
> ./localNetworkDown.py [interface*] [router_ip*] [victim_ip]
```
You can find out the required interface through a ifconfig or iwconfig. You can find out the IP address of the gateway through **nmap**.