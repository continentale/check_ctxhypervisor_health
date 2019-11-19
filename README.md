# check_ctxhypervisor_health

check_ctxhypervisor_health checks the health of a Citrix Hypervisor (and Xenserver) via XenApi.

### System requirements: 
* php with modules xml-rpc and curl

### Usage example

./check_ctxhypervisor_health -h=192.168.1.20 -u=root -p=rootpwd -w=95 -c=99

##ä Parameters
* -h ip or hostname 
* -u username, typically root
* -p password from the user
* -w warning threshold for ram usage / disk usage
* -c critical threshold for ram usage / disk usage
