# Instalar
  Para que funcione se debe instalar los paquetes: 
````
sudo pacman -S vicious xcompmgr nitrogen lxappearance terminator scrot
````

# Complementos
  En caso que no tengas instalado el escritorio, firefox y nautilus
````
sudo pacman -S awesome firefox nautilus
````
## Configuración
- Luego proceder a clonar este repositorio dentro de la carpeta
````
~/.config
````

- En caso de desear iniciar desde cero creamos un directorio .config y podemos copiar el contenido de ejemplo de la fuente para modificarlo a nuestro gusto.
`````
mkdir ~/.config/awesome && cp /etc/xdg/awesome/rc.lua ~/.config/awesome/
`````

Teclado en español:
`````
setxkbmap -layout distribución_xkb
`````

Para hacerlo permanente puede colocarlos en .bashrc

