# Debian Upgrader
Simple script básico para actualizar los sistemas Linux basados en Debian.

## Installation
* Si quieres usar el script como un comando del sistema, puedes mover el script a `/usr/local/bin` u otro directorio que esté en el PATH (`echo $PATH`).
* Asegúrate de que el script tenga los permisos de ejecución y nada más.
* Es necesario tener instalado `aptitude`, aunque puedes adaptar el script para usar apt en vez de aptitude.

```bash
sudo apt-get install -fy aptitude
```

## Usage
Con el script en `/usr/local/bin` (o algún lugar del PATH) puedes ejecutar
```bash
sudo update
```
Si no, usa `sudo ./update` estando ubicado en la carpeta del script.

## License

[MIT](https://choosealicense.com/licenses/mit/)
