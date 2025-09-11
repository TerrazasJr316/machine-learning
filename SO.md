# Comandos

```bash
sudo su # Privilegios de administrador
```

su → manda al super usuario (root)

```bash
sudo pacman -Syu / -Syyu
```

actualizar sistema y/o respositorios

pacman es el sistema gestor de paquetes.

tiene 3 bases de datos:

* archarcraft.db actualiza los paquetes de la distro
* cure.db las update del nucleo que son 2 (kernel: controla haciendo comunicación con el so y firmware: driver y controladores com red)
* extra.db paquetes de apps que no son parte de la distro

recononcer app que no pertenezcan al kernel:

```bash
sudo pacman -Ss nombre_app (vscode)
```

la s es para buscar

instalar al app

```bash
sudo pacman -S code
```

se usa sudo para actualizar los directorios del root 
se intalará en el direc /etc o /bin o /lib
su es más vulnerable a ataques de red
con sudo se esta dando los privilegios de root

otro sistema gestor de paquetes:

```bash
yay -Syyu
yay -Ss tilix
yaay -S tilix git code
```

comnda para listar archivos

```bash
ls
```

para ocultar archivos

```bash
.git # el punto lo tomara como una extension
```

listar archivos visible y ocultos

```bash
ls -a # listar todos los archivos con persmisos fehcas y autores
ls -la # Listar TODOS los archivos
```

comando que permita leer archivos (en texto en primer plano)

```bash
cat archvio.txt
cat archivo.js
cat archivo.py
```

moficar el archivo

```bash
nao archivo.py
vim archivo.py
nvim archivo.py
```

renombrar archivos

```bash
mv archivo.py archivo2.py
```

mover archivos

```bash
mv archivo.py directorio/archivo.py
mv directorio/archivo.py directorio2/codigos/archivo.py
```

otros

```bash
rm archivo.py # borrar archivos
mkdir directorio3/ # crear directorios
pwd # ubicación de la carpeta
neofetch # características del sistema

top # administrador de tareas
htop
man
```