# Jarkom-Modul-5-IT30
- Refaldi
- Anisa Ghina Salsabila 5027211062

Pembagian Subnet

![Screenshot 2023-12-20 151122](https://github.com/anisaghinasalsabila/Jarkom-Modul-4-IT30-2023/assets/71119774/eb97f226-114f-4fc2-94ea-f73a791342df)

VLSM 

![Screenshot 2023-12-20 151313](https://github.com/anisaghinasalsabila/Jarkom-Modul-4-IT30-2023/assets/71119774/856ebbd5-d47c-4aab-a2c9-25b8c6c1d4d9)

Tree


![Untitled(11)](https://github.com/anisaghinasalsabila/Jarkom-Modul-4-IT30-2023/assets/71119774/7785b777-ba66-4e37-9a81-f8fd4922d006)

Konfigurasi 
- Revolte
```
  # Static config for eth0
auto eth0
iface eth0 inet static
	address 192.248.14.134
	netmask 255.255.255.252
	gateway 192.248.14.133
	up echo nameserver 192.248.14.150 > /etc/resolv.conf
```
- Richer
```
# Static config for eth0
auto eth0
iface eth0 inet static
	address 192.248.14.150
	netmask 255.255.255.252
	gateway 192.248.14.149
	up echo nameserver 192.168.122.1 > /etc/resolv.conf
```
- Fern
```
# Static config for eth0
auto eth0
iface eth0 inet static
	address 192.248.14.2
	netmask 255.255.255.128
	gateway 192.248.14.1
	up echo nameserver 192.248.14.150 > /etc/resolv.conf

# Static config for eth1
auto eth1
iface eth1 inet static
	address 192.248.14.149
	netmask 255.255.255.252

# Static config for eth2
auto eth2
iface eth2 inet static
	address 192.248.14.133
	netmask 255.255.255.252
```
- SchewerMountain1
```
# DHCP config for eth0
auto eth0
iface eth0 inet dhcp
```
- LaubHills
```
# DHCP config for eth0
auto eth0
iface eth0 inet dhcp
```
- Himmel
```
# Static config for eth0
auto eth0
iface eth0 inet static
         address 192.248.14.146
         netmask 255.255.255.252
         gateway 192.248.14.145
	 up echo nameserver 192.248.14.150 > /etc/resolv.conf

auto eth1
iface eth1 inet static
         address 192.248.14.1
         netmask 255.255.255.128

auto eth2
iface eth2 inet static
         address 192.248.12.1
         netmask 255.255.254.0
```
- Frieren
```
# Static config for eth0
auto eth0
iface eth0 inet static
         address 192.248.14.138
         netmask 255.255.255.252
         gateway 192.248.14.137
	 up echo nameserver 192.248.14.150 > /etc/resolv.conf

auto eth1
iface eth1 inet static
         address 192.248.14.141
         netmask 255.255.255.252

auto eth2
iface eth2 inet static
         address 192.248.14.145
         netmask 255.255.255.252
```
- Stark
```
# Static config for eth0
auto eth0
iface eth0 inet static
         address 192.248.14.142
         netmask 255.255.255.252
         gateway 192.248.14.141
	 up echo nameserver 192.168.122.1 > /etc/resolv.conf
```
- Aura
```
auto eth0
iface eth0 inet static
    address 192.168.122.14
    netmask 255.255.255.0
    gateway 192.168.122.1

auto eth1
iface eth1 inet static
      address 192.248.14.129
      netmask 255.255.255.252

auto eth2
iface eth2 inet static
       address 192.248.14.137
       netmask 255.255.255.252

```
- Heiter
```
auto eth0
iface eth0 inet static
         address 192.248.14.130
         netmask 255.255.255.252
         gateway 192.248.14.129
	 up echo nameserver 192.168.122.1 > /etc/resolv.conf

auto eth1
iface eth1 inet static
         address 192.240.8.1
         netmask 255.255.252.0

auto eth2
iface eth2 inet static
         address 192.240.0.1
         netmask 255.255.248.0
```
