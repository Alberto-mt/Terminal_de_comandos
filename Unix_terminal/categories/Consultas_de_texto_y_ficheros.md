## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Consultas de texto y ficheros
[![UNIX](https://img.shields.io/badge/Consultas_de_texto_y_ficheros-447ac0?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Consultas_de_texto_y_ficheros.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **grep root [ubicación de fichero]**  | Sacar las líneas que contengan la palabra o patrón en un fichero  |
| **grep ^root [ubicación de fichero]**  | Líneas que empiecen por root  |
| **grep root$ [ubicación de fichero]<br>grep root:/bin/bash$ [ubicación de fichero]**  | Líneas que acaben por root  |
| **grep -n error /var/log***  | Líneas de coincidencia con la palabra (error) de cada fichero, sacará el número de todos los errores  |
| **grep -n error /var/log/auth.log**  | Líneas de coincidencia con la palabra (error) de un fichero, sacará el número de todos los errores  |
| **grep -c error /var/log/auth.log**  | Número de errores de un archivo con la palabra error  |
| **grep -c error /var/log/***  | Número de errores de todos los archivos del directorio log, con la palabra error  |
| **ls -lh \/ \| grep bin**  | A la salida de un comando (bin)  |
| **find /etc -name "*.conf"**  | Buscar cualquier archivo, que se llame como sea, pero que tenga la extensión ".conf"  |
| **find / -size +1024k -size -2024k**  | Buscar por tamaño del archivo (mayor a 1024k y menor a 2024K)  |
| **find . -name "[texto a consultar]\*"**  | Buscar en el directorio actual el fichero que contenga el texto a consultar  |
| **find . -iname "[texto a consultar].\*"**  | Buscar en el directorio actual el fichero que contenga el texto a consultar, ignorando mayúsculas y minúsculas  |

#### Ejemplo
```bash
grep root /etc/passwd

grep ^root /etc/passwd

grep root$ /etc/passwd
grep root:/bin/bash$ /etc/passwd

grep -n error /var/log*

grep -n error /var/log/auth.log

grep -c error /var/log/auth.log

grep -c error /var/log/*

ls -lh / | grep bin

find /etc -name "*.conf"

find / -size +1024k -size -2024k

find . -name "test*"

find . -iname "test.*"
```

[![UNIX](https://img.shields.io/badge/Consultas_de_texto_y_ficheros-447ac0?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Consultas_de_texto_y_ficheros.md)
