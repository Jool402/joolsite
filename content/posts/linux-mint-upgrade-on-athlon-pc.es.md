---
title: "Actualización de Linux Mint en PC Athlon"
date: 2024-07-26T12:35:58-04:00
draft: false
---

En artículos anteriores mencioné una de mis PCs que ejecuta Linux con una CPU Athlon 64. HP construyó una de ellas, por lo que ha pasado años desde que salió Windows XP.

Pasó por una fase de salto de distribución de Arch Linux a Linux Mint. Puse Arch Linux, Debian, Linux Mint, NixOS, etc. No todo salió bien. Las distribuciones que fallaron fueron Gentoo y KISS Linux.

Muchas distribuciones de Linux funcionaron de inmediato, pero finalmente volví a las primeras tres distribuciones mencionadas en la lista. Si bien Gentoo se instaló correctamente en esta PC, el tiempo de compilación fue abismal porque mi computadora Athlon 64 ya tiene casi dos décadas. El programa que más tiempo me llevó programar en mi PC fue LLVM. Incluso sospeché que Gentoo se congelaba durante la compilación de LLVM. En el caso de KISS Linux, simplemente dejé de instalarlo porque tardaba demasiado en instalarse.

Finalmente, me decidí por Linux Mint. Elegí específicamente Linux Mint XFCE porque la edición XFCE de Linux Mint es la versión más liviana que se encuentra en el sitio web de Linux Mint. Linux Mint cargó un par de ediciones más: Cinnamon Edition, XFCE Edition y MATE Edition.[^1] MATE es decente para computadoras antiguas, pero XFCE consume menos recursos. Cinnamon es el más pesado de los tres porque se basa en la bifurcación de GNOME 3.

Instalé Linux Mint mediante la primera parte de la instalación OEM. La instalación OEM configura el disco duro e instala la distribución en él. Además, configuré la computadora utilizando la segunda parte de la instalación. La segunda parte configura Linux Mint después de instalar la distribución en el disco. Ambas partes de la instalación OEM se realizaron correctamente.

Sin embargo, dejé mi PC Athlon 64 allí durante tantos días; por lo tanto, mi PC no se ha utilizado desde entonces. La razón por la que dejé de usar esta PC es porque obtuve una más nueva y más rápida.

A fines de junio de 2024, encendí mi PC Athlon 64 y el escritorio se veía limpio y sin archivos personales. Sin embargo, el sistema operativo estaba muy desactualizado. (La última actualización probablemente tenía un año o dos de retraso). Fue porque la PC quedó fuera durante mucho tiempo.

Como solución, actualicé Linux escribiendo `sudo apt update` y `sudo apt upgrade` en el terminal sin ventanas. La actualización tardó unos treinta minutos. Cuando finalizó la actualización de Linux Mint, el entorno de escritorio se veía limpio y actualizado.

El único problema real era el ruido de mi PC Athlon 64. La PC era ruidosa en comparación con mis otras PC. De repente, encontré una solución poco apropiada y sin relación con el problema: cambié el controlador de gráficos del controlador no oficial Nouveau por un controlador oficial de NVIDIA. Esto hizo que mi PC se silenciara.

Aunque el escritorio predeterminado Linux Mint XFCE se veía elegante, cambié el tema del escritorio y de los íconos a Mint-Y-Dark-Blue, ya que el azul es mi color favorito.

Con mi vieja PC actualizada, ¿quién sabe qué haré con esta computadora en los próximos días? Estoy pensando en el uso que le daré a mi PC Athlon 64. Tengo muchas otras computadoras con las que jugar. Con el tiempo, estaré demasiado ocupado para usar la PC Athlon 64.

[^1]: https://www.linuxmint.com/download.php
