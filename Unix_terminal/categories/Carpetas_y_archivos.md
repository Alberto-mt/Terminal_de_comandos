## Unix terminal
[![UNIX](https://img.shields.io/badge/UNIX_TERMINAL-FCC624?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/index.md)

### Carpetas y archivos
[![UNIX](https://img.shields.io/badge/Carpetas_y_archivos-c044b8?style=for-the-badge&logo=GNOMETERMINAL&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Carpetas_y_archivos.md)

#### Descripción de comandos
| Comando  | Descripción  |
|:-:|---|
| **cd**  | Cambiar de directorio  |
| **ls**  | Listar directorio actual  |
| **ls -l**  | Listar directorio actual con formato de listado |
| **ls -lha**  | Listar directorio actual con formato de listado más amplio y mostrando directorios ocultos |
| **ls -d**  | Mostrar directorio actual  |
| **ls lhR**  | Mostrar directorio actual y contenido del directorio  |
| **ls -lh /home**  | Mostrar listado de otro directorio  |
| **mkdir ejercicios/unix -p**  | Crear carpetas  |
| **pwd**  | Mostrar directorio donde estoy actualmente  |
| **cd /ejercicios/**  | Ir a directorio  |
| **cd ..**  | Ir a directorio anterior  |
| **rmdir unix/**  | Eliminar directorio  |
| **rmdir -rf unix/**  | Eliminar el directorio de forma recursiva y forzada (aunque tenga archivos)  |
| **touch documento.txt**  | Crear fichero  |
| **echo "Hola mundo" > documento.txt**  | Meter contenido al fichero  |
| **echo "Hola mundo 2" >> documento.txt**  | Seguir metiendo contenido al fichero  |
| **cat documento.txt**  | Mostrar contenido del fichero  |
| **nano documento.txt**  | Editor de código nano (abrir fichero y escribir en él)  |
| **vi documento.txt**  | Editor de código vi (abrir fichero y escribir en él)  |
| **:wq**  | Guardar y salir del fichero  |
| **mv documento.txt ejercicios/documento.txt**  | Mover archivo a otra carpeta  |
| **cp ejercicios/\* ./**  | Copiar todos los archivos al directorio actual  |
| **df -h**  | Espacio disponible en el equipo  |
| **du /bin**  | Cuanto espacio ocupa una carpeta  |
| **du -h /bin<br>du -hs /bin**  | Cuanto espacio ocupa una carpeta en megas  |

#### Ejemplo
```bash
cd home

ls
ls -l
ls -lha
ls -d
ls -lhR
ls -lh /home

mkdir ejercicios/unix -p

pwd

cd /ejercicios/

cd ..

rmdir unix/

rmdir -rf unix/

touch documento.txt

echo "Hola mundo" > documento.txt

echo "Hola mundo 2" >> documento.txt

cat documento.txt

nano documento.txt

vi documento.txt

:wq

mv documento.txt ejercicios/documento.txt

cp ejercicios/* ./

df -h

du /bin
du -h /bin
du -hs /bin
```

[![UNIX](https://img.shields.io/badge/Carpetas_y_archivos-c044b8?style=for-the-badge&label=&#9650;&logoColor=white&labelColor=101010)](https://github.com/Alberto-mt/Terminal_de_comandos/blob/main/Unix_terminal/categories/Carpetas_y_archivos.md)
