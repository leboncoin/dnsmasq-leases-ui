# dnsmasq-leases-ui

This tool provides a web based ui for leases file of the famous DNS/DHCP daemon [dnsmasq](http://thekelleys.org.uk/dnsmasq/doc.html).

# Example

A `/var/lib/misc/dnsmasq.leases` file with the following content

```
1504409608 11:11:11:11:11:11 192.168.0.10 Client1 01:11:11:11:11:11:11
1504409397 22:22:22:22:22:22 192.168.0.18 Client2 *
0 33:33:33:33:33:33 192.168.0.1 ServerWithStaticIP 01:33:33:33:33:33:33
```

will produce


![Screenshot 1](https://raw.githubusercontent.com/fschlag/docs/master/dnsmasq-leases-ui-docs/screenshot_1.png)

# How to use

After cloning the repository run `python dnsmasq-leases-ui.py`

The web interface will be available under `http://<hostname or ip>:5000`
