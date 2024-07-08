![Preview](https://raw.githubusercontent.com/brunojardon/DebianUpgrader/main/preview.webp)
# Debian Upgrader
Simple script básico para actualizar los sistemas Linux basados en Debian usando el administrador de paquetes APT.

## Instalación
* Si quieres usar el script como un comando del sistema, puedes mover el script a `/usr/local/bin` u otro directorio que esté en el PATH (`echo $PATH`).
* Asegúrate de que el script tenga los permisos de ejecución y nada más.
* Opcionalmente puedes instalar aptitude, el script utilizará una combinacion de apt y aptitude.

```bash
sudo apt install -y aptitude
```

## Uso
Con el script en `/usr/local/bin` (o algún lugar del PATH) puedes ejecutar
```bash
sudo update
```
Si no, usa `sudo ./update` estando ubicado en la carpeta del script.

## Licencia

[MIT](https://choosealicense.com/licenses/mit/)
