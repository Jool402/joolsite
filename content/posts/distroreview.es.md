---
title: "Comentarios sobre Distribuciones"
date: 2024-07-24T15:44:22-04:00
draft: false
---

He probado varias distribuciones en tres computadoras. Muchas distribuciones populares tienen la reputación de ser robustas para un usuario de Linux. Luego, hay distribuciones de Linux menos utilizadas que crearon un concepto nuevo e inteligente. En contraste, algunas distribuciones de Linux no funcionaron en mis computadoras por alguna razón.

Estoy usando una Dell Inspiron con una pantalla táctil que se puede girar 360°. Conecto un disco duro externo al puerto USB de mi computadora portátil para poder realizar un arranque dual. La combinación de USB 3.0 y disco duro no es la combinación más rápida, los dos son más lentos que SATA y NVMe. Sin embargo, una distribución de Linux arranca bien con ellas.

Mi computadora de escritorio es un PC prefabricado. Tiene una unidad NVMe que tiene Windows 11 instalado. Además, tiene un disco duro SATA donde instalé Arch Linux.

Tengo un par de Raspberry Pis: el primero ejecuta Raspberry Pi OS (Raspberry Pi 5) y el otro ejecuta Lineage OS 20. Cambiaré los sistemas operativos en el futuro. Ambos funcionan con tarjetas SD. También tengo el tercero Pi más potente del mercado.

## Ubuntu
Probé Ubuntu GNOME en mi Raspberry Pi 4. El sistema operativo no funciona a la perfección; al menos, funciona bien para una computadora con reputación de ser lenta. Continué instalando Xubuntu en el dispositivo y funcionó mejor porque el escritorio XFCE es más rápido que el entorno de escritorio GNOME. Más tarde, instalé el sistema operativo predeterminado de Raspberry Pi en mis Raspberry Pis. Tengo dos de los Raspberry Pi con mejor rendimiento. Tuve el Raspberry Pi 5 hace dos días para probar algunas distribuciones. Ahora que los tengo, puedo probar distribuciones de Linux ARM64/AARCH64 en mi última Pi (también conocida como PIve).

## Debian
Debian fue una de las primeras distribuciones que ejecuté en una computadora. Comencé ejecutando Debian precargado en una BeagleBone® Black. Luego también instalé Debian. Es estable; sin embargo, no le gusta actualizarse de una versión estable a una versión sid en un terminal GUI. Si un usuario actualiza completamente Debian escribiendo los comandos en el tty, la distribución debería estar lista para actualizarse.

## Linux Mint
Linux Mint fue la primera distribución que instalé en mi disco duro externo. No probé Linux Mint en profundidad, pero sí lo instalé temporalmente en mi disco duro durante un breve período. Usé el disco duro externo para conectarlo a uno de los dos puertos USB de mi computadora portátil (no quería borrar el sistema operativo Windows, ya que todavía lo necesito para algunas aplicaciones).

## Fedora
Después de probar Linux Mint, llegó el momento de ejecutar Fedora. Fedora funcionó muy bien en mi sistema. Últimamente, he tenido problemas con esta distribución. Uno de los problemas de Fedora en mi disco duro externo es que sigue fallando. La falla ocurrió incluso después de actualizar la distribución a su última versión, incluso después de la instalación. Podría deberse a que el disco duro a veces se desconecta de mi computadora de manera invisible. También podría deberse a que Fedora está actuando mal en mi dispositivo. Sigo ejecutando Fedora en el disco externo conectado a pesar de los problemas.

## OpenSUSE
Intenté instalar OpenSUSE en el disco duro porque quería probar algo diferente. Lamentablemente, ni siquiera pude instalar esta distribución en mi disco duro. El instalador no incluye la segunda unidad en mi máquina virtual. Parecía una distribución elegante para probar. Tiene la exclusiva herramienta de administración YaST para OpenSUSE.

## Arch Linux
Arch Linux ha estado funcionando en mi computadora de escritorio desde que lo coloqué en el dispositivo de almacenamiento secundario del disco duro SATA. Nunca probé Arch en mi nueva computadora portátil, pero sí lo probé en una de mis netbooks. Incluso instalé Arch en una Beagleboard: la primera computadora que ha ejecutado Linux.

## Conclución
Me he decidido por Fedora en mi disco externo, pero todavía estoy considerando si seguir usando Fedora o usar una distribución diferente. No puedo estar seguro de si el problema que describí antes fue un problema del disco duro externo o un problema de Fedora. Todavía tengo Windows 11 en el SSD interno de mi computadora portátil. Lo mismo se aplica a mi computadora de escritorio.

Me quedo con Arch Linux para mi computadora de escritorio. Arch Linux tiene reputación de romperse después de actualizarse porque Arch Linux es una distribución de lanzamiento continuo. Sin embargo, ha estado funcionando bien, así que no estoy pensando en sobrescribir Windows con Arch Linux porque necesito que se ejecute software exclusivo de Windows.

La Raspberry Pi 5 ejecuta el sistema operativo oficial. La estabilidad y la función de este sistema operativo es un efecto de Debian. Por otro lado, la Raspberry Pi 4 ejecuta LineageOS 20. Ambos funcionan bien en común.

Ocasionalmente encuentro problemas, pero muchos de estos problemas se pueden resolver (excepto ese error de Fedora que escribí en la sección que cubre Fedora).
