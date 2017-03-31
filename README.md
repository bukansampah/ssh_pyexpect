
## Usage example

```
$ ./ssh_expect.py --u myuser --p mypasswd --h router101 --cmd "show version|no-more; show system uptime|no-more"
Password:mypasswd

--- JUNOS 15.1F6-S4.2 Kernel 32-bit  JNPR-10.3-20161130.340898_build
myuser@router101> show version|no-more
show version|no-more
Hostname: router101
Model: mx960
...deleted...

myuser@router101>  show system uptime|no-more
show system uptime|no-more
Current time: 2017-01-31 10:45:54 EDT
Time Source:  NTP CLOCK
System booted: 2016-12-24 11:12:43 EST 
...deleted...

myuser@router101> exit
```
