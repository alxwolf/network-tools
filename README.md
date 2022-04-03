# network-tools
Collection of scripts and tools for network setup

## MAC address generator

This [MAC address generator](https://gist.github.com/INA2N/079adda7d6e5612996e4e993152d7103) will provide a random MAC address.

Run with

```bash
[UDM] root@udm-pro:/mnt/data/podman/cni# ./macgen.sh 
EE:CC:EC:A2:7C:D1
```

## ULA generator

This [python script](https://github.com/n-st/python-ula) will provide a unique, valid prefix for IPv6 Unique Local Addresses (starting with fdxx:...).

Run with

```bash
[UDM] root@udm-pro:/mnt/data# python ula.py
fdca:5c13:1fb8::
```