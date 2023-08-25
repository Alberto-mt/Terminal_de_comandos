## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Red
[![UNIX](https://img.shields.io/badge/Red-447ac0?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Red.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **ifconfig**  | Ver configuración IP etc  |
| **ifdown [interfaz por ejemplo eth0]**  | Desactivar una interfaz  |
| **ifup [interfaz por ejemplo eth0]**  | Activar una interfaz  |
| **/etc/init.d/networking restart<br> o <br>service networking restart**  | Reiniciar el servicio de red  |
| **ping -c[numero de peticiones] URL**  | Hacer ping a url  |

#### Cambiar dns
```bash
/etc/resolv.conf

#Configuración básica del fichero:
nameserver [ip dns]
nameserver 8.8.8.8
```

#### Cambiar dirección IP, máscara y puerta de enlace
```bash
/etc/network/interfaces
 
# Interface Loopback, necesaria para localhost
auto lo
iface lo inet loopback
 
# Configuración ip dinámica DHCP:
allow-hotplug eth0
iface eth0 inet dhcp
 
# Configuración ip estática:
auto eth0
iface eth0 inet static
        address 192.168.0.60
        gateway 192.168.0.1
        netmask 255.255.255.0
        network 192.168.0.0
```

#### Ejemplo
```bash
ifconfig

ifdown eth0

ifup eth0

/etc/init.d/networking restart
# o
service networking restart

ping -c 4 https://www.google.es/
```

[![UNIX](https://img.shields.io/badge/Red-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Red.md)
