# Jarkom-Modul-3-B13-2022

### Kelompok B13

<table>
    <tr>
        <th>No</th>
        <th>Nama</th>
        <th>NRP</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Nathanael Roviery</td>
        <td>5025201258</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Elbert Dicky Aristyo</td>
        <td> 5025201231</td>
    </tr>
    <tr>
        <td>3</td>
        <td>Amsal Herbert</td>
        <td>5025201182</td>
    </tr>
</table>

### Konfigurasi Network

Ostania

```
auto eth0
    iface eth0 inet dhcp

auto eth1
    iface eth1 inet static
    address 192.185.1.1
    netmask 255.255.255.0

auto eth2
    iface eth2 inet static
    address 192.185.2.1
    netmask 255.255.255.0

auto eth3
    iface eth3 inet static
    address 192.185.3.1
    netmask 255.255.255.0
```

SSS

```
auto eth0
iface eth0 inet static
    address 192.185.1.2
    netmask 255.255.255.0
    gateway 192.185.1.1
```

Garden

```
auto eth0
iface eth0 inet static
    address 192.185.1.3
    netmask 255.255.255.0
    gateway 192.185.1.1
```

Wise

```
auto eth0
iface eth0 inet static
    address 192.185.2.2
    netmask 255.255.255.0
    gateway 192.185.2.1
```

Berlint

```
auto eth0
iface eth0 inet static
    address 192.185.2.3
    netmask 255.255.255.0
    gateway 192.185.2.1
```

Westalis

```
auto eth0
iface eth0 inet static
    address 192.185.2.4
    netmask 255.255.255.0
    gateway 192.185.2.1
```

Eden

```
auto eth0
iface eth0 inet static
    address 192.185.3.2
    netmask 255.255.255.0
    gateway 192.185.3.1
```

NewstonCastle

```
auto eth0
iface eth0 inet static
    address 192.185.3.3
    netmask 255.255.255.0
    gateway 192.185.3.1
```

KemonoPark

```
auto eth0
iface eth0 inet static
    address 192.185.3.4
    netmask 255.255.255.0
    gateway 192.185.3.1
```
