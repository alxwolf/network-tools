# network-tools

Collection of scripts and tools for network setup

## MAC address generator

This [MAC address generator](https://gist.github.com/INA2N/079adda7d6e5612996e4e993152d7103) will provide a random MAC address.

Install with

```bash
curl -Lo macgen.sh https://gist.githubusercontent.com/INA2N/079adda7d6e5612996e4e993152d7103/raw/2e770f82f85794f7e4ee959b39112df9c04b3c71/macgen.sh && chmod +x macgen.sh
```

Run with

```bash
[UDM] root@udm-pro:/mnt/data/podman/cni# ./macgen.sh 
EE:CC:EC:A2:7C:D1
```

## ULA generator

This [python script](https://github.com/n-st/python-ula) will provide a unique, valid prefix for IPv6 Unique Local Addresses (starting with fdxx:...).

Install with

```bash
curl -Lo ula.py https://raw.githubusercontent.com/n-st/python-ula/master/ula.py
```

Run with

```bash
[UDM] root@udm-pro:/mnt/data# python ula.py
fdca:5c13:1fb8::
```
