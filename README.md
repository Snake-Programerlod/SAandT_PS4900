# Este host esta optimizado para ejecutar Kernel Exploit en el firmware 9.00
---
## Resumen
Este host tiene como finalidad ejecutar el Kernel Exploit en el firmware 9.00, para lograr liberar la consola y poder habilitar HEN 2.0

## Short how-to
Este exploit es diferente a los anteriores en los que se basaban puramente en software. Para desencadenar la vulnerabilidad, es necesario conectar un dispositivo USB formateado especialmente en el momento adecuado. para ello vamos a grabar una imagen iso utilizando la herramienta Win32DiskImager en una usb, dicha imagen la podran descargar desde el 

![](https://i.imgur.com/qpiVQGo.png)

Cuando ejecute el exploit en la PS4, espere hasta que llegue a una alerta con "Inserte USB ahora. No cierre el cuadro de diálogo hasta que aparezca la notificación, retire el USB después de cerrarlo". Como indica el cuadro de diálogo, inserte el USB y espere hasta que aparezca la notificación "Formato de disco no admitido", luego cierre la alerta con "Aceptar".

El exploit puede tardar un minuto en ejecutarse y la animación giratoria en la página puede congelarse; está bien, déjela continuar hasta que aparezca un error o tenga éxito y muestre "En espera de carga útil".

## Notas
- Debes insertar el USB cuando aparezca la alerta, luego déjalo ahí un rato hasta que aparezcan las notificaciones de almacenamiento de la ps4.
- Desenchufe el USB antes de un (re) ciclo de arranque o correrá el riesgo de dañar el montón del kernel en el arranque (no nos hacemos responsables por algun daño que se pueda presentar)
- El navegador puede tentarlo a cerrar la página antes de tiempo, no lo haga.
- El círculo de carga puede congelarse mientras se activa el exploit webkit, esto no significa nada.
- Este error funciona en ciertos firmwares de PS5, sin embargo, no hay una estrategia conocida para explotarlo en este momento, "ALERTA" no se recomienda usar en PS5.


## Todos los creditos a los desarrolldores del WebKit para 9.00 y del Kernel Exploit.
- laureeeeeee
- [Specter](https://twitter.com/SpecterDev)
- [Znullptr](https://twitter.com/Znullptr)
- [Andy Nguyen](https://twitter.com/theflow0)
- [sleirsgoevy](https://twitter.com/sleirsgoevy) - [9.00 Webkit exploit](https://gist.github.com/sleirsgoevy/6beca32893909095f4bba1ce29167992)

