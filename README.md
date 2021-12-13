# Este host esta optimizado para ejecutar el kernel exploit para PS4 firmware 9.00
---
## Resumen

Este host esta realizado con la finalidad de poder liberar nuestra consola PS4 con firmware 9.00

## Instrucciones
Este exploit es diferente a los anteriores en los que se basaban puramente en software. Para desencadenar la vulnerabilidad, es necesario conectar un dispositivo USB formateado especialmente en el momento adecuado, para ello se debera grabar una imagen .img en un usb utilizando el programa Win32DiskImager, la imagen se proporcionara en el video tutorial.

! [] (https://i.imgur.com/qpiVQGo.png)

El exploit puede tardar un minuto en ejecutarse y la animación giratoria en la página puede congelarse; está bien, déjela continuar hasta que aparezca un error o tenga éxito y muestre "En espera de carga útil".

## Notas
- Debes insertar el USB cuando aparezca la alerta, luego déjalo ahí un rato hasta que aparezcan las notificaciones de almacenamiento de la ps4.
- Desenchufe el USB antes de un (re) ciclo de arranque o correrá el riesgo de dañar el montón del kernel en el arranque, puede causar kernel panic, si no se siguen las instrucciones (no nos hacemos responsables).
- El navegador puede tentarlo a cerrar la página antes de tiempo, no lo haga.
- El círculo de carga puede congelarse mientras se activa el exploit webkit, esto no significa nada.
- Este error funciona en ciertos firmwares de PS5, sin embargo, no hay una estrategia conocida para explotarlo en este momento.

## ALERTA NO USAR EN PS5

## Todos los creditos y agradecimientos a los desarrolladores del webkit y kernel exploit.
- laureeeeeee
- [Specter](https://twitter.com/SpecterDev)
- [Znullptr](https://twitter.com/Znullptr)
- [Andy Nguyen](https://twitter.com/theflow0)
- [sleirsgoevy](https://twitter.com/sleirsgoevy) - [9.00 Webkit exploit](https://gist.github.com/sleirsgoevy/6beca32893909095f4bba1ce29167992)
