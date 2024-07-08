![Preview](https://raw.githubusercontent.com/brunojardon/SysUp/main/preview.webp)
<h1 align="center">SysUp</h1>
Simple script básico para actualizar los sistemas Linux basados en Debian usando el administrador de paquetes APT.

<h2>Instalación</h2>

1. Clona el repositorio.
2. Dentro del directorio, mueve el archivo update a `/usr/local/bin/`.
3. Reinicia la terminal.

```bash
git clone --depth=1 https://github.com/BrunoJardon/SysUp.git
cd ./SysUp/
sudo mv ./update /usr/local/bin/
```

<h2>Funcionamiento</h2>
El script se debe ejecutar como usuario root usando.

```bash
sudo update
```

Esto ejecutara

~~~
apt update            # Actualiza los repositorios
apt upgrade -y        # Actualiza los programas basicos
apt dist-upgrade -y   # Actualiza la distribucion
apt full-upgrade -y   # Actualiza el sistema y desinstala los paquetes no requeridos
apt autoremove -y     # Para asegurar
apt clean             # Borra la cache (/var/cache/apt/archives/)
~~~

Tambien revisara si es necesario reiniciar la computadora

<h2>Licencia</h2>
[MIT](https://choosealicense.com/licenses/mit/)
