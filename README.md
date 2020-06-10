Basado en el repositorio del usuario de github Pusty
[realmode-assembly](https://github.com/Pusty/realmode-assembly/tree/master/part7)

##  Tanques booteable

La idea fundamental de este juego es crear una serie de laberintos u obstáculos por los cuales una cierta cantidad de tanques buscarán matar un águila la cual está protegida por paredes, las cuales se desvanecerán si reciben balan por parte de la casa.

El juego contará con un tanque dirigido por el usuario y su función es derribar a los otros tanques para resguardar el águila. Este tanque posee balas infinitas para derrotar a los otros.

El juego tendrá tres niveles de dificultad. Para pasar de nivel, es necesario derrotar al menos 4 tanques por nivel si el águila recibe un disparo se acaba el juego.

El juego deberá proveer en todo momento la cantidad de tanques derrotados y el nivel de juego (principiante-medio-avanzado) que se está llevando a cabo. También es importante que se muestren los comandos en pantalla como parte de la guía para el usuario.

Cuando el jugador gana el tercer nivel, el juego permitirá la opción de reiniciar o salir, además debe de desplegar un mensaje en pantalla con alguna animación (movimiento) de felicitaciones por haber ganado. Se podrá reiniciar el juego en cualquier instante, así como finalizarlo.

El tanque se moverá en las direcciones que le indique el usuario, los posibles comandos son:
• Flecha derecha: El tanque se moverá hacia la derecha.
• Flecha izquierda: El tanque se moverá hacia la izquierda.
• Flecha abajo: El tanque se moverá hacia abajo.
• Flecha arriba: El tanque se moverá hacia arriba.
• Espacio: El tanque disparará.
• L: Pausa el juego y lo reanuda de la misma manera.
• R: Reinicia el juego.

## Requerimientos

1. Instalar nasm para linux:

```bash
sudo apt intall nasm
```

2. Instalar qemu para linux:

```bash
sudo apt intall qemu
```

## Instalación

1. Para correr en Qemu sin ser booteable

```bash
make
```

2. Para hacer el USB booteable se debe descargar el programa HDD raw copy en el cual

* Se selecciona el archivo de ./bin/booteable_tanks.bin
* Se selecciona el USB a formatear.
* Se presiona start.


## Contribuyendo
* [Mauricio Álvarez Varela.](https://github.com/mau18alvarez)
* [Juan Esquivel Rojas.](https://github.com/JDesq)
* [Álvaro Quesada Ramirez.](https://github.com/varoqr08)
