# Instalar
  Para que funcione se debe instalar los paquetes: 
````
sudo pacman -S awesome vicious xcompmgr nitrogen lxappearance xscreensaver terminator scrot
````
## Configuración
- Luego proceder a clonar este repositorio dentro de la carpeta ~/.config/awesome
````
git clone https://github.com/TecladoZurdo/awesome.git ~/.config/awesome
````

- En caso de desear iniciar desde cero creamos, podemos copiar el contenido de ejemplo para modificarlo a nuestro gusto.
`````
mkdir ~/.config/awesome && cp /etc/xdg/awesome/rc.lua ~/.config/awesome/
`````
- Luego para ver los cambios puedes ejecutar
`````
win + ctrl + r
`````
para refrescar la pantalla

## Doble monitor

Para los que usan dos monitores instalar
`````
sudo pacman -S xorg-xrandr
`````

Luego configurar dependiendo de los conectores que dispone el equipo
 - ver las conecciones actuales
`````
xrandr
`````

Ejecutar la configuracion deseada en mi caso es
`````
xrandr --output HDMI3 --auto --output HDMI2 --auto --right-of HDMI3
`````

Teclado en español:
`````
setxkbmap -layout distribución_xkb
`````

Para hacerlo permanente puede colocarlos en .bashrc

