# Simple Firewall
Our homework.

## Force Quit
if firewall crash/freeze, run the following command:

```shell
ps -aux | grep lpfw
kill -9 [PID]
sudo iptables -F
```