# EVOPRO — versión de prueba (piloto)

**EVOPRO** es un programa de escritorio para diseñar y mostrar montajes de eventos (congresos, convenciones, reuniones)
dentro de un salón de hotel, en plano 2D y en 3D.

Esta es una **versión piloto**: está en desarrollo y todavía le faltan cosas. Se agradece cualquier comentario.

## Cómo instalarlo

Necesitás **Windows 10 u 11 de 64 bits**. No hace falta instalar nada más.

1. Descargá el instalador **`EVOPRO-0.1.0-x64.exe`** (o la versión `.zip`, que no se instala: se descomprime y se abre
   `EVOPRO.exe`).
2. Abrilo. Windows puede avisar **«Windows protegió su PC»** porque el programa todavía no está firmado digitalmente:
   tocá **Más información → Ejecutar de todas formas**.
3. Seguí los pasos del instalador. Al terminar queda un acceso directo «EVOPRO» en el escritorio y en el menú Inicio.

Para desinstalarlo: Configuración de Windows → Aplicaciones → EVOPRO → Desinstalar.

### Requisitos

- 8 GB de memoria (4 GB alcanzan para montajes chicos) y unos 500 MB de disco.
- Cualquier placa de video con WebGL 2 (alcanzan los gráficos integrados).
- **NDI es opcional** (solo para recibir video de Resolume, vMix u OBS en las pantallas LED). El programa funciona entero
  sin NDI; si querés usarlo, instalá «NDI Tools».

## Cómo probarlo (5 minutos)

1. Al abrir, en **Inicio** tocá **Nuevo**. Se crea un salón de 20 × 16 m con una puerta.
2. Pestaña **Salón**: cambiá las medidas, agregá paredes divisorias, columnas, techo y alfombra.
3. Pestaña **Montaje**: arrastrá equipos de la biblioteca al plano o al 3D: trusses, torres de iluminación, luces, pantallas LED,
   proyectores con su pantalla de tela, tarimas con entelado, tótems de TV…
4. Pestaña **Mobiliario y decoración**: tocá **Armar sillas y mesas…** y probá Banquete, Auditorio y Escuela; también hay
   mesas, sillas, vajilla, florero, anotadores y personas.
5. **Presentación ▸ Modo demo (F5)** recorre el salón con la cámara; **Esc** sale.
6. Guardá con **Ctrl+S**. **Ctrl+Z** deshace casi todo.

Ayudas que ya están en el programa:

- **F1**: guía con buscador («¿Cómo hago…?» y lista de todos los comandos).
- **Ayuda al pasar el cursor**: la franja de abajo explica lo que hay bajo el mouse.

## Qué nos interesa que cuentes

- Lo que no se entiende, o no se ve bien, o se traba.
- Lo que esperabas que hiciera y no hizo.
- Cualquier cartel de error (una captura de pantalla ayuda mucho).

## Datos

- Los proyectos se guardan como archivos **`.montaje`** y los salones preparados como plantillas.
- Las preferencias y las plantillas quedan en la carpeta de datos del usuario de Windows; no se toca nada más de la PC.
- Las bibliotecas que usa el programa y sus licencias están en `LICENCIAS-TERCEROS.md`.

## Descargas

Entrá a **[Releases](../../releases/latest)** y bajá:

- `EVOPRO-0.1.0-x64.exe`: instalador (recomendado).
- `EVOPRO-0.1.0-x64.zip`: versión sin instalar (se descomprime y se abre `EVOPRO.exe`).

Este repositorio solo contiene las descargas de la versión piloto; el código no es público.
