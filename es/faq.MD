---
layout: page
title: Preguntas frecuentes
lang: es
permalink: /es/faq/
ref: faq
---

<style>
p:not(.outside) {margin: 1em 0 1em 2.5rem!important; border-bottom: 1px solid rgba(0,0,0,0.25); padding-bottom: 1rem;}
p.noline,blockquote p {border-bottom: 0px!important; padding-bottom: 0px!important;}
</style>

<p class="outside">Esta página intenta proporcionar respuesta a alguna de las preguntas que recibimos con mayor frecuencia.</p>

# General

### ¿Por qué me interesaría usar Subsurface?

Subsurface proporciona a buceadores recreativos, técnicos y profesionales una interfaz simple y fácil de usar para planificar, registrar y organizar inmersiones. Las inmersiones se pueden introducir manualmente, desde hojas de cálculo, directamente desde otro software de divelog y, lo más importante, desde muchos ordenadores de buceo. ¿Qué pasa si cambias de ordenador de buceo? Esto no es un problema con Subsurface ya que no depende del fabricante de un ordenador concreto. Los buzos técnicos apreciarán el planificador que les permite planificar usando VPM-B o Bülmann ZH-L16. Con él resulta sencillo comprobar gases de reserva, comparar diferentes mezclas de gases y factores de gradiente y, finalmente, es fácil imprimir el plan. Subsurface es gratuito y está disponible en múltiples plataformas, lo que lo convierte en el software perfecto para un amplio elenco de buceadores.

### ¿Que sistemas operativos soporta Subsurface?

Subsurface corre en Windows (32 y 64bit, Windows 10 y más recientes), MacOS (Intel, 10.15 y más recientes) y muchas distribuciones de Linux. Las versiones para dispositivos móviles de Subsurface están disponibles para Android e iOS y facilitan una plataforma portable para visualizar tu divelog y efectuar pequeñas ediciones.

Se proporcionan paquetes de Linux para Ubuntu, Linux Mint, Debian, openSUSE y Fedora. También están disponibles un paquete Snap y una AppImage genérica para otras distribuciones de Linux. Para más detalles sobre donde encontrar Subsurface para tu SO visita la página de [Descargas](https://subsurface-divelog.org/download/).

Subsurface-mobile está disponible está disponible en Google Play y en la App Store de iTunes.

### ¿Cuanto cuesta Subsurface?

Subsurface es software de código abierto. Usarlo es gratis. Ha sido escrito por un grupo de entusiastas que hacen esto en su tiempo libre, incluidos proporcionar el almacenamiento en la nube y el resto de infraestructura. Entiende, por favor, que esto también significa que responderán a tus peticiones cuando tengan tiempo, y que, en general, no aprecian que les traten como al equipo de soporte de una firma comercial. Si prefieres un programa de divelog comercial, hay un montón de ellos donde elegir.

### Por favor, añadid la siguiente funcionalidad estupenda

Como comentábamos en la cuestión anterior, Subsurface está escrito y mantenido por voluntarios. También tiene varias decenas de miles de usuarios. El conjunto actual de funcionalidades intenta mantener un balance razonable entre simplicidad en la experiencia de usuario y la integración de las funcionalidades más demandadas.  Las nuevas funcionalidades, a menudo, se rechazan si ninguno de los desarrolladores aprecia que pueden suponer una diferencia significativa para la mayoría de nuestros usuarios.

### El consumo de gas/CAS reportado por Subsurface está mal

Lo más probable es que esperes que el cálculo de consumo de gas siga la ingenua Ley de los Gases Ideales. Desafortunadamente los gases reales no son gases ideales y Subsurface [tiene en cuenta la compresibilidad de los gases](https://thetheoreticaldiver.org/wordpress/index.php/2017/11/02/when-real-gas-corrections-matter/).

# Soporte de Sistemas Operativos (SO)

## Windows

### ¿Como instalo Subsurface en Windows?

[Descarga el instalador](https://subsurface-divelog.org/download/) y haz doble clic en él. Aparecerá un aviso de que el instalador es de un editor desconocido (aunque debe identificar al editor como Dirk Hohndel). Selecciona "Sí"  para permitir la instalación. A continuación se presentará la licencia de Subsurface, tras lo que podrás elegir donde prefieres instalar Subsurface (la opción por defecto resultará razonable en la mayoría en la mayoría de los casos) y la carpeta del menú "Inicio" donde se instalará un atajo para lanzar Subsurface y una entrada para el desinstalador.

### Versiones soportadas

Subsurface se ejecuta en Windows 10 y más recientes. Debería de correr también en Windows 8. Las versiones más antiguas ya no están soportadas.

### ¿Donde encuentro los archivos "log" en Windows?

Los logs están en `C:\Users\Home\AppData\Roaming\Subsurface` en los dos archivos `subsurface_out.log` y `subsurface_err.log`

### ¿Qué drivers necesito para mi ordenador de buceo?

Buena pregunta. Comúnmente son específicos para la combinación de ordenador de buceo y cable de descarga que utilices. Y es realmente complicado dar respuestas universalmente correctas a la pregunta.

### ¿Hay un virus en el instalador de Subsurface?

Si te aparece un mensaje de aviso o si Subsurface es bloqueado por tu antivirus (AV), es casi con total seguridad un falso positivo. Subsurface no se compila en una máquina Windows, se construye por compilación cruzada en Linux en un servidor limpio y bien mantenido.
<br /> <!-- adding an empty line in the .MD file creates a new paragraph which in turn creates a separator line when rendered -->
La mayoría, si no todos, los paquetes de software antivirus para Windows soportan la funcionalidad "añadir excepción", que evita que un ejecutable sea escaneado. Intenta añadir Subsurface a la lista de software no dañino. Si la descarga del instalador de Subsurface se detecta como malware, desactiva temporalmente tu software AV hasta que Subsurface esté instalado.
<br />
En cualquier caso, por favor, informa a tu proveedor de software AV del "falso positivo", ya que te aseguramos que Subsurface no es malware.

### Subsurface deja de acceder a la nube de repente

Puede haber muchos motivos para ello, pero uno realmente extraño que nos hemos encontrado es que algunos productos anti-malware en Windows, de forma aparentemente aleatoria, deciden que el tráfico de red entre Subsurface y el servidor de la nube es una indicación de actividad de malware e interrumpen la transmisión. Esto puede llevar a corrupción de datos en la nube y evita que las cosas funcionen. Es posible que tengas que añadir una excepción para Subsurface en tu herramienta anti-malware hiper agresiva.

## macOS

### ¿Como instalo Subsurface en MacOS?

[Descarga el instalador](https://subsurface-divelog.org/download/) DMG y abrelo. Arrastra el icono de Subsurface hasta el icono de Aplicaciones.

### Versiones soportadas

Subsurface corre en Macs Intel con macOS 10.15 o más reciente. Subsurface corre en Macs M1 en modo de emulación Rosettastone.

### ¿Se pueden compilar binarios para versiones más antiguas de macOS?

Apple dejo de dar soporte a macOS 10.14 y anteriores. No podemos tampoco dar soporte para esas versiones más antiguas de macOS.

### No puedo descargar de mi ordenador de buceo Bluetooth desde macOS 12 / Monterey

Es un problema conocido. Estamos trabajando en una solución pero, actualmente, la única opción es descargar usando un dispositivo móvil con Subsurface-mobile y sincronizar dispositivos usando la nube de Subsurface.

### ¿Existe una versión nativa de Subsurface para los Macs basados en Apple M1?

Varias de las librerías clave en las que se basa Subsurface solo tienen un soporte incompleto para los Macs basados en M1. Estamos trabajando en una compilación limitada en M1, pero, de momento, te funcionarán mejor los binarios basados en Intel.

### ¿Por qué no me funciona mi ordenador de buceo que transmite por IRDA (infrarrojos) en un Mac?

Subsurface en el Mac no soporta, en estos momentos, ordenadores de buceo basados en infrarrojos. Es un problema derivado de falta de librerías que den ese soporte. Otros softwares de divelog puede que hayan implementado su propia pila para infrarrojos en Mac, pero nosotros no.  Subsurface en Windows y Linux soportan los ordenadores de buceo basados en infrarrojos perfectamente.

## Linux

### Versiones soportadas

Subsurface puede ejecutarse en la mayoría de distribuciones de Linux. Los desarrolladores mantienen compilaciones para las versiones actuales de Ubuntu, Linux Mint, Debian, openSUSE y Fedora. También hay Snap y AppImage de Subsurface para otras distribuciones. En general, prueba el binario específico de una distribución y, si no funciona, intenta con el Snap o la AppImage.

### ¿Podéis añadir binarios para mi distribución favorita de Linux?

Añadir soporte para otra distribución de Linux es, en general, una montaña de trabajo y, dado el pequeño número de usuarios, probablemente no suceda. Pero, por favor, avísanos si crees que hay una distribución que debería añadirse en lugar de las que soportamos en la actualidad.

### ¿Puedo compilar mis propios binarios?

Claro. En general es bastante sencillo (asumiendo que estás un poco familiarizado con el desarrollo en C/C++ en Linux). El archivo `INSTALL` en el directorio de código fuente debería ponerte en marcha. Contacta con nuestros desarrolladores si necesitas más ayuda de la que aparece en dicho archivo (porque eso significaría, probablemente, que hay que actualizar el archivo `INSTALL`).

# Soporte de dispositivos móviles

### ¿Como instalo Subsurface-mobile en mi teléfono / tablet?

Para Android e iOS simplemente instala las apps Subsurface-mobile que están disponibles en las respectivas app stores. Activa el almacenamiento en la nube desde tu PC y guarda en la nube de Subsurface tu información de buceo. Así tendrás las inmersiones disponibles también en tu dispositivo móvil. Subsurface-mobile no tiene todas las funciones de la versión de escritorio de Subsurface. Por ejemplo, la planificación no está disponible en Subsurface-mobile y algunos tipos de ordenador de buceo no pueden descargar inmersiones directamente a Subsurface-mobile, sin embargo, sí se pueden añadir inmersiones manualmente.

Para el resto de dispositivos (incluyendo tablets y teléfonos con SOs que no soportamos con Subsurface-mobile), puedes abrir nuestra [página web de la nube](https://cloud.subsurface-divelog.org/) y logarte con la misma dirección de email / password. Esto te permitirá acceder a tus datos de buceo desde cualquier dispositivo con un navegador web.

## Android

### ¿Cual es la versión de Android mínima requerida?

Actualmente la mínima es is Android 8.0

### Desde qué ordenadores de buceo puede descargar directamente Subsurface?

Los ordenadores de buceo basados en Bluetooth o BLE, así como USB serie deberían funcionar en general (suponiendo que estén soportados por Subsurface, desde luego).  Los que no funcionan son otros dispositivos USB, como USB HID (por  ejemplo la familia Suunto EON Steel), USB storage (por ejemplo el Uemis Zurich), MIP (por ejemplo, Garmin).

### La última versión en beta-test no funciona

Esto sucede de vez en cuando. A menudo se soluciona rápidamente, en ocasiones es un problema más obstinado que puede llevar un tiempo solucionar. La solución alternativa más simple suele ser, simplemente, abandonar el programa beta, esperar un tiempo (para que se sincronicen los servidores de Google), desinstalar Subsurface-mobile, esperar un poco más y reinstalarlo. De esta forma pasarás a estar en una versión de producción que debería funcionar bien.

## iOS

### ¿Desde que ordenadores de buceo puede descargar directamente Subsurface en iOS?

Solo ordenadores Bluetooth y BLE (que ya estén soportados en Subsurface). No es posible la descarga basada en cable.

# Uso

### ¿Como sé si tengo la última versión de Subsurface?

Desde el menú "Ayuda", selecciona "Comprobar actualizaciones".
También puedes dirigirte a la sección [Noticias](https://subsurface-divelog.org/category/news/) de la página web de Subsurface en la que aparecen los anuncios de nuevas versiones.

### ¿Como puedo importar mis inmersiones a Subsurface?
<p class="noline">Hay muchas formas de importar a Subsurface. Del Manual de Usuario,</p>
<p class="noline">Para inmersiones registradas manualmente:</p>
> Para añadir una inmersión a un divelog, selecciona Registro → Añadir inmersión en el menú principal. El programa mostrará tres paneles en los que incorporar información de una inmersión: dos pestañas en el panel Info (Notas y Equipo), así como el panel Perfil de Inmersión que muestra un perfil gráfico de cada buceo.

<p class="noline">Para importar desde un ordenador de buceo:</p>
> Un ordenador de buceo se puede conectar al PC del usuario siguiendo estos pasos:
> - El cable de interfaz debería estar conectado a un puerto USB libre (o la conexión Bluetooth o infrarroja establecida como se detallará luego en este manual).
> </br>
> - El ordenador de buceo debería estar en modo de comunicación. (Revisa el manual del ordenador de buceo concreto).
> </br>
> - En Subsurface, desde el Menú Principal, selecciona Importar → Importar del ordenador de buceo.

Luego sigue las indicaciones para seleccionar tu ordenador de buceo en particular. Se puede encontrar información más detallada en el Manual de Usuario.
<br />
Existe también la posibilidad de añadir inmersiones desde otros softwares o páginas web. Dirígete al Manual de Usuario para la información más actualizada sobre este tema.  Puedes encontrarla en la Sección 5.3 (Nota del traductor, la versión inglesa del manual suele estar actualizada. La española está muy desfasada).

### ¿Como puedo usar más de una botella con el mismo gas?

Esta es una pregunta típica de buceadores en side-mount o buzos técnicos. Subsurface soporta tener más de una botella con el mismo gas, incluso aunque algunos ordenadores de buceo no lo hagan. Simplemente añade un cambio de gas a tu segunda botella y ambas se incluirán en los cálculos de gases. Para añadir el cambio de gas, simplemente haz clic derecho en el perfil en el punto adecuado y se te ofrecerá la posibilidad de añadir el evento.

### ¿Por qué no es capaz Subsurface de descargar mis inmersiones de mi ordenador de buceo?

Limpia los contactos. Vuelve a limpiar los contactos. Asegúrate de que el cable está conectado firmemente. Muévelo. En serio. Asegúrate de que el ordenador de buceo está en modo de transferencia de datos (esto no es necesario para todos los ordenadores, pero sí para mucho habituales). Comprueba con otro software que la descarga funciona en general.  Prueba con otro cable. Revisa el Manual de Usuario en relación al emparejamiento por Bluetooth y el caso de uso general.

### ¿Por qué está fallando la importación de CSV?

Hay un par de advertencias para la importación desde CSV. Deberías evitar algunos caracteres especiales como el "signo comercial" (&), "menor que" (<), "mayor que" (>) y las comillas dobles ("), este último si está acotando campos de texto. El archivo debería usar el conjunto de caracteres UTF-8 si tiene caracteres no ascii. También puede causar problemas el tamaño del archivo CSV. Importar bloques de 100 inmersiones (sin perfil de inmersión) cada vez ha funcionado bien, pero archivos más grandes pueden exceder los límites del analizador que usamos. Si tienes problemas para importar desde CSV, inténtalo primero con una muestra más pequeña para comprobar si funciona correctamente

### ¿Como puedo usar Subsurface para múltiples usuarios?

Potencialmente la mejor forma de conseguir esto es utilizar diferentes usuarios en el ordenador. Todos los sistemas operativos soportan usuarios múltiples. De esta forma la configuración de Subsurface para cada usuario está separada de verdad.
<br />
Potencialmente, la forma más fácil de conseguir esto es guardar los registros de los diferentes usuarios en archivos distintos. Desde Subsurface puedes abrir archivos individuales para diferentes buceadores y funciona bien. El problema con esta solución es que es incompatible con el almacenamiento en la nube de Subsurface.
<br />
Una mezcla de las dos opciones sería cuando deseas ejecutar Subsurface con varios usuarios desde un único usuario del ordenador. Subsurface tiene la posibilidad de hacer esto también, simplemente lanza Subsurface con la opción *--user*, por ejemplo --user=joebloggs. Desde este espacio de trabajo exclusivo del este usuario puedes abrir divelogs guardados localmente o en la nube.

### ¿Como puedo cargar fotografías y asociarlas con mi inmersión?

Selecciona las inmersiones con las que deseas asociar las fotografías. Luego haz clic derecho en uno de los buceos seleccionados y elige "Cargar imágenes" del menú desplegable que aparecerá. Con esto te aparecerá un diálogo de selección donde podrás elegir una o varias fotos. Cuando tengas terminada la selección y pulses Abrir, te aparecerá un nuevo diálogo donde puedes correr las horas de las imágenes. Esto se describe con más detalle en el Manual de Usuario.
<br />
Si tienes problemas con la carga de imágenes, comprueba si tienes al menos una de las siguientes etiquetas en las cabeceras Exif: DateTimeOriginal o DateTime. Tomamos la hora desde estos campos para detectar si la foto se tomó durante la inmersión o no. Si la foto está editada, deberías guardar la información Exif original en la imagen nueva/editada para que se cargue correctamente.

### ¿Puedo importar mis buceos desde mi viejo software de divelog?

Muchos programas habituales ya están soportados y siempre nos alegra intentar añadir nuevos. Si tu viejo software soporta exportar el divelog, probablemente podamos importarlo (por ejemplo vía archivos CSV o UDDF). Sin embargo, importar el formato nativo te permitirá obtener una información más completa en Subsurface, como caso general. Para poder implementar soporte para el formato original, necesitaremos un divelog de ejemplo. Sería también estupendo disponer de algunas capturas de pantalla del software original o una descripción de lo que se mostraría en el ejemplo de divelog. Preferiblemente nos interesaría tener una inmersión razonablemente simple para conseguir un soporte básico inicial y otra inmersión que tenga activadas tantas funciones como sea posible (por ejemplo, cambios de gas durante el buceo).  Por favor envía esta información al foro de usuarios o a la lista de correo de los desarrolladores subsurface@subsurface-divelog.org. Desafortunadamente algunos de los formatos de divelog no hemos sido capaces de descifrarlos (ya que algunos vendedores han decidido encriptar sus divelogs para incrementar el grado de dependencia de sus clientes), así que no hay garantías de que esto permita soportar tu viejo software, pero merece la pena intentarlo.

### ¿Como descargo inmersiones desde mi ordenador Bluetooth (e.g., Shearwater, OSTC)?

Descargar inmersiones usando Bluetooth se hace en todas las plataformas usando la opción "Elegir modo de descarga Bluetooth" en el desplegable de Descargar desde el Ordenador de Buceo, y haciendo el emparejamiento con el ordenador de buceo detectado. Esto se explica en más profundidad en el [Manual de Usuario de Subsurface](https://subsurface-divelog.org/documentation/subsurface-4-user-manual/).
<br />
Las versiones más antiguas de Subsurface requerían ajustar una conexión RFCOMM desde la línea de comandos antes de descargar inmensiones desde un ordenador de buceo con Bluetooth, pero ya no es el caso.

### ¿Como descargo inmersiones desde mi ordenador de buceo Bluetooth LowEnergy, BLE, Bluetooth Smart (e.g., Shearwater Perdix AI, Shearwater Perdix (latest models), Suunto EON Steel)?

En estos momentos (Febrero de 2022, Subsurface 5.0.6 / Subsurface-mobile 3.4.1) las versiones actualmente disponibles de Subsurface y Subsurface-mobile soportan la conexión a ordenadores de buceo a través de BLE en todas las plataformas, con la excepción de macOS 12. Hemos visto informes en los que las AppImages en Linux fallan al conectar a dispositivos  BT/BLE, pero los paquetes nativos en Linux funcionan.

### No consigo descargar todas mis inmersiones, solo las más recientes, aunque el manual de mi computador de buceo afirma que guarda el historial de, por ejemplo, 999 buceos.

El historial de buceo es diferente de los perfiles de inmersión del registro. El historial solo conserva rastro del total de inmersiones y el tiempo total pasado bajo el agua. Los registros, por otra parte, conservan el perfil de inmersión, pero disponen de una cantidad limitada de memoria para hacerlo. La cantidad exacta de perfiles que pueden guardarse en un dispositivo dependen del intervalo de las muestras y de la duración de los buceos. Una vez que la memoria se ha llenado se sobrescriben las inmersiones más antiguas con nuevas. De esta forma, solo podemos descargar las últimas 13, 30 o 199 inmersiones.
<br />
Si has descargado tus inmersiones a otro software de divelog antes de que se sobreescribieran hay muchas posibilidades de que Subsurface pueda importarlas. Sin embargo, si los registros solo estaban en el computador de buceo, no pueden ser recuperados después de haber sido sobreescritos por nuevas inmersiones.

### ¿Qué hacer cuando falla la autenticación con el almacenamiento en la nube?

Si has configurado correctamente tus credenciales de Subsurface y el almacenamiento en la nube aún falla, intenta cambiar el password en las preferencias de Subsurface. Ha habido un cambio en el servicio en la nube que puede provocar un fallo de sincronización, pero un cambio de password lo soluciona.
<br />
Si tus credenciales siguen sin funcionar, o hay alguna otra cosa mal, contacta con Dirk para solucionarlo.

### ¿Puede Subsurface guardar mis archivos en un servidor en la nube diferente?

Subsurface puede guardar tu divelog seguro en la nube, sirviendo como copia de respaldo de tus datos, permitiéndote ver tus divelogs en un escritorio, o en Android o iOS apps.  Solo hay un servidor en la nube disponible (https://cloud.subsurface-divelog.org) lo que permite a los desarrolladores mejorar Subsurface, solucionar problemas y dar soporte a los usuarios (con su permiso) si algo falla.  Todo esto resulta imposible de gestionar si existen diferentes servidores en la nube.
<br />
Si deseas guardar una copia de backup de tu divelog en un servidor remoto, la documentación describe como guardar tus datos en Dropbox u otros servicios similares como TeamDrive, MiniBox, etc.

### ¿Como puedo limpiar mis ajustes?

En ocasiones tus ajustes pueden terminar siendo erróneos o haberse corrompido. Eso sería bastante raro, pero cuando suceda hay dos opciones para resolver el problema.
<br />
Una, si aún puedes correr Subsurface, abre las Preferencias, selecciona "Reiniciar" al final del panel izquierdo.
<br />
Si eso no funciona, las cosas se complican y pasan a depender del Sistema Operativo.
<br />
En Windows es necesario borrara las claves del Registro de Subsurface.
<br />
En macOS es necesario borrar `~/Library/Preferences/org.hohndel.subsurface.Subsurface.plist`  (El hecho de que se incluya el nombre `hohndel` es resultado de una decisión desafortunada hace un montón de tiempo que es bastante difícil de deshacer sin romper cosas).
<br />
En Linux, la ubicación de los ajustes dependen de varios factores pero, habitualmente, es `~/.config/Subsurface/Subsurface.conf`
<br />
Oh, y todos estos nombres cambian si estás usando la función `--user=...` para disponer de diferentes ajustes para diferentes usuarios.

# Problemas con ordenadores de buceo concretos

### ¿Podéis añadir soporte para el ordenador X?

Ya soportamos un gran número de ordenadores de buceo y siempre estamos encantados de dar soporte a más.  Por favor, contacta con nosotros a través del foro de usuarios para que podamos intentar ayudar. Algunos fabricantes nos han ayudado activamente en nuestro trabajo y dar soporte a nuevos modelos de estos fabricantes suele ser sencillo.  Otros fabricantes son más neutrales y algunos activamente hostiles. Sin la ayuda del fabricante suele ser muy complicado resolver el protocolo de transferencia y la codificación de las inmersiones usando ingeniería inversa, pero con ayuda suficiente por tu parte a menudo es posible hacerlo.
<br />
Un buen punto de inicio suele ser enviarnos un log y un volcado de libdivecomputer (puedes seleccionarlos en el diálogo de Descarga desde el ordenador de buceo), cuando te conectes a un ordenador de buceo usando un modelo parecido (si es posible).

### Ordenadores de buceo Suunto de estilo antiguo

La mayoría de los cables de descarga están basados en FTDI y necesitan los drivers apropiados. Algunos cables de terceros necesitan drivers diferentes. Sin esos drivers, el ordenador de buceo no se mostrará. Una vez puedas ver el dispositivo (`COMn` or `/dev/tty...`), si tienes tiempos de espera o errores de datos, visita la <a href="#i-get-timeouts-or-data-error-when-downloading">pregunta sobre errores de datos</a>.

### Tengo tiempos de espera o errores de datos al descargar

Resulta pasmosa la frecuencia con la que los motivos son unos contactos húmedos o sucios, o una batería baja. No importa si el ordenador de buceo se enciende. Los modos de descarga suelen necesitar voltajes altos y estables para funcionar. Y, lamentablemente, incluso hemos visto una situación en la que el software del fabricante funcionaba (porque puede hacer un trabajo mucho mejor corrigiendo errores), pero Subsurface no descargará hasta que tengas una batería cargada y los contactos limpios y secos de verdad.

### Las descargas con BLE (Bluetooth Low Energy) son increíblemente lentas

Sí, sí lo son. Ya que Subsurface soporta descargas BLE de muchos ordenadores de buceo diferentes de muchos fabricantes distintos, el código, a menudo, no está tan bien ajustado para un ordenador concreto como lo puede estar el software del fabricante. Así pues, desafortunadamente, estas descargas son dolorosamente lentas. Habitualmente descargar unas pocas inmersiones al día es tedioso, pero no horrible. Pero una descarga, especialmente la inicial, con cien o más inmersiones puede llevar una hora o más (y en ocasiones es difícil completarla sin incurrir en errores que la pueden abortar). De verdad vale la pena descargar a menudo. Y, si el ordenador de buceo ofrece la posibilidad de descargar con un cable USB (además de BLE, como por ejemplo la familia Suunto EON Steel), es, definitivamente, preferible para esa primera descarga.

## Garmin Descent

### ¿Soporta Subsurface-mobile el Garmin Descent?

Los ordenadores de buceo Descent solo están soportados en Windows, macOS, y Linux, y solo para descargas por cable. No hay planes para soportar descargas por BLE en ninguna de las plataformas.

### ¿Puedo importar archivos '.FIT' directamente?

Si por algún motivo no puede funcionar la descarga normal, pero tienes acceso a los archivos `.FIT`, puedes usar Subsurface para importarlos (o mejor aún, descargarlos). Simplemente crea una carpeta `...algunaruta.../Garmin/Activity` y copia los archivos `.FIT` a esa carpeta. Inicia una descarga de Subsurface e introduce `...algunaruta...`(sin la parte de `Garmin/Activity`) en el campo "Dispositivo o punto de montaje" y pulsa Descargar.

### El Garmin Descent Mk2/Mk2i no quiere conectarse

El Descent Mk2/Mk2i es un dispositivo MTP, lo cual da problemas ocasionalmente al intentar descargar a Subsurface. MTP soporta una única conexión, por tanto otras apps MTP pueden evitar que Subsurface se conecte al ordenador de buceo. Cierra las aplicaciones del tipo "Transferencia de archivos de Android".

### Garmin Descent Mk2/Mk2i en Windows

Necesitas el driver USB correcto para "hablar" con el Descent Mk2/Mk2i:<br>- descarga [Zadig 2.6](https://zadig.akeo.ie/) y ejecútalo<br>- conecta el Descent y selecciona MTP<br>- espera a que Zadig te ofrezca el Descent como opción (esto puede necesitar que desconectes y vuelvas a conectar el cable)<br>- selecciona el Descent y pídele a Zadig que instale `libusb-win32` (espera a que termine, lo que puede tardar un poco)<br>- desenchufa el Descent y vuelve a enchufarlo, de nuevo seleccionando MTP<br>- ahora Subsurface puede descargar de él (no introduzcas nada en el campo de conexión)

# Otras preguntas

Si tu pregunta no se ha respondido aquí, comprueba el [Foro de usuarios](https://subsurface-divelog.org/user-forum/) (prueba con la función de búsqueda) y, si no encuentras respuesta allí, abre un nuevo tema y pide ayuda.

<p class="outside"> Este FAQ es mantenido en <a href="https://github.com/subsurface/subsurface.github.io">GitHub</a> -- las PRs son bienvenidas.  <p>


