# Política de Privacidad de Milli

**Fecha de entrada en vigor:** 1 de agosto de 2026
**Última actualización:** 3 de octubre de 2026

## La versión resumida

Milli no recopila tus datos. No existe ningún servidor de Milli, ni análisis,
ni publicidad, ni seguimiento, ni SDK de terceros. Todo lo que introduces
permanece en tu dispositivo y — solo si activas la sincronización con
iCloud — en tu propia cuenta privada de iCloud, a la que no podemos acceder.

## Quiénes somos

Milli ("la app") está desarrollada por **IVAN CAYABYAB** ("nosotros").

Para cualquier pregunta sobre esta política o tu privacidad, contáctanos en
**ivnsjdev@gmail.com**.

## Qué almacena Milli, y dónde

Milli es una app de finanzas personales. La información que introduces se
almacena en tu dispositivo, en una base de datos local. Nunca la recibimos.

| Lo que introduces | Dónde vive | ¿Lo vemos? |
| --- | --- | --- |
| Transacciones, importes, notas, fechas | En tu dispositivo | No |
| Cuentas y libros contables | En tu dispositivo | No |
| Categorías y presupuestos | En tu dispositivo | No |
| Pagos recurrentes y recordatorios | En tu dispositivo | No |
| Cifras de referencia salarial que introduces | En tu dispositivo | No |
| Foto de perfil | En tu dispositivo | No |
| Ajustes y preferencias de la app | En tu dispositivo | No |
| Palabras que Milli aprende de tus correcciones en el chat | En tu dispositivo | No |
| Transacciones que introduces en el Apple Watch | En tu Apple Watch, y luego en tu iPhone | No |

No recopilamos, transmitimos, vendemos, alquilamos ni compartimos nada de
esto, porque la app no tiene capacidad para enviarlo a ningún sitio. Milli no
realiza solicitudes de red a ningún servidor operado por nosotros ni por
terceros.

## Smart Chat e inteligencia en el dispositivo

El **Smart Chat** de Milli te permite registrar una transacción
escribiéndola en lenguaje natural — "café 4,50" o "compra 62 ayer" — y Milli
deduce por ti el importe, la categoría y la fecha.

Todo esto ocurre **en tu dispositivo**. Milli usa la inteligencia en el
dispositivo de Apple y las funciones de texto en el dispositivo integradas en
iOS, con un sencillo lector basado en reglas como alternativa cuando aquellas
no están disponibles. No hay ningún servidor de IA: tu mensaje se lee en el
dispositivo y nunca se envía a nosotros ni a ningún tercero.

Cuando eliges o corriges la categoría de una nota, Milli recuerda esa palabra
para que la misma nota se clasifique por sí sola la próxima vez. Estas
asociaciones aprendidas entre palabra y categoría se almacenan solo en tu
dispositivo, junto con el resto de tus datos, y nunca se transmiten. Puedes
consultarlas, y eliminar cualquiera de ellas, en la app. Milli no usa lo que
escribes, ni nada más que introduzcas, para entrenar ningún modelo de
aprendizaje automático.

## Sincronización con iCloud (opcional)

Si activas la sincronización con iCloud, Milli usa CloudKit de Apple para
copiar tus datos en la **base de datos privada de tu propia cuenta de
iCloud**, de modo que puedan aparecer en tus otros dispositivos iniciados con
la misma cuenta de Apple.

- Estos datos se almacenan bajo tu cuenta de Apple, no la nuestra.
- No tenemos acceso a ellos ni capacidad para leerlos, exportarlos o
  recuperarlos.
- Apple procesa estos datos tal como se describe en la
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Puedes desactivar la sincronización con iCloud en cualquier momento desde los
ajustes de la app, o desactivarla para todo el sistema en **Ajustes → tu
nombre → iCloud** en tu dispositivo.

## Apple Watch

Milli incluye una app para Apple Watch, disponible como parte de las
funciones premium, para ver las cifras de hoy y añadir transacciones desde
tu muñeca.

**Cómo llegan los datos hasta ahí.** La app del reloj no tiene base de
datos, ni cuenta, ni acceso a la red propio. Todo lo que muestra llega
directamente desde tu iPhone emparejado a través de **WatchConnectivity**,
el enlace del sistema entre un iPhone y el Apple Watch emparejado con él.
Ese enlace es de dispositivo a dispositivo, gestionado por iOS y watchOS; no
pasa por ningún servidor nuestro, y ningún dato de Milli se nos envía en
ningún momento.

**Qué viaja por el enlace.** Solo lo que necesita la pantalla del reloj: tus
cuentas y sus nombres, iconos, colores y divisas; las transacciones de hoy y
la cifra neta de hoy para esas cuentas; los nombres e iconos de tus
categorías; tus preferencias de idioma y formato numérico; y si las
funciones premium están desbloqueadas. Todo tu historial de transacciones,
notas, presupuestos y la foto de perfil permanecen en el iPhone. En la otra
dirección, una transacción que introduces en el reloj viaja al iPhone como
un importe, una categoría y una cuenta, y se guarda en tu libro contable
allí.

**Qué conserva el reloj.** El reloj almacena la instantánea más reciente que
recibió, además de cualquier transacción que hayas introducido y que el
iPhone aún no haya confirmado, en el almacenamiento privado propio de la app
en el propio reloj. Esto es lo que permite que la app se abra con cifras
reales, y que puedas registrar gastos, cuando tu iPhone está fuera de
alcance. Cualquier cosa introducida mientras ambos están separados se
conserva en el reloj hasta que el iPhone vuelve a estar disponible, momento
en el que se le entrega.

- La app del reloj **no** usa iCloud, y no conserva ninguna copia de tus
  datos fuera del reloj.
- La app del reloj **no** realiza solicitudes de red.
- **No** accede a datos de salud, actividad física, frecuencia cardíaca,
  entrenamientos o ubicación, y no solicita ese tipo de permisos.

**Para eliminar la copia del reloj,** desinstala Milli del reloj — en el
reloj, mantén pulsado el icono de la app y elimínala, o en el iPhone abre la
app **Watch**, selecciona Milli y desactiva *Show App on Apple Watch*.
Desemparejar el reloj borra también sus apps y sus datos.

## Face ID, Touch ID y bloqueo con código

Si activas el bloqueo de la app, Milli le pide a iOS que te autentique. Tus
datos biométricos son gestionados por completo por Secure Enclave de Apple y
**nunca se comparten con la app** — iOS le indica a Milli únicamente si la
autenticación tuvo éxito o falló. Si estableces un código de acceso de la
app, se almacena solo en tu dispositivo.

## Cámara y biblioteca de fotos

Milli solicita acceso a la cámara o a la biblioteca de fotos únicamente
cuando eliges establecer una foto de perfil. La imagen se almacena en tu
dispositivo (y en tu propio iCloud, si la sincronización está activada).
Milli no sube fotos a ningún sitio ni accede a tu biblioteca en segundo
plano.

## Notificaciones

Si activas los recordatorios para pagos recurrentes, Milli programa
**notificaciones locales** en tu dispositivo. Estas se generan en el propio
dispositivo mediante iOS. No interviene ningún servidor de notificaciones
push y ningún contenido del recordatorio sale de tu dispositivo.

## Compras

Milli ofrece una compra dentro de la app de pago único para desbloquear las
funciones premium. La compra la procesa íntegramente **Apple** a través de
la App Store. Nunca recibimos tus datos de pago, número de tarjeta o
dirección de facturación. Milli solo le pregunta a Apple si la cuenta de
Apple actual es propietaria de la compra, para saber si debe desbloquear las
funciones premium. La app del Apple Watch no puede consultar por sí misma a
la App Store, así que el iPhone le indica a través del mismo enlace privado
si la compra está desbloqueada — un único valor de sí o no, sin ninguna
información de pago en él. Las compras se rigen por los
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Copias de seguridad que exportas

Milli te permite exportar un archivo de copia de seguridad de tus datos. Una
vez lo exportas, ese archivo queda bajo tu control y esta política ya no lo
protege — dondequiera que lo guardes o lo envíes (Files, iCloud Drive,
correo electrónico, otra app) se rige por los términos de ese servicio.
Trata un archivo de copia de seguridad como tratarías un extracto bancario.

## Widgets

Los widgets de pantalla de inicio de Milli leen una pequeña cantidad de tus
datos desde un área de almacenamiento privada compartida entre la app y su
propia extensión de widget en tu dispositivo. Nada de esa área compartida se
transmite fuera del dispositivo.

## Lo que Milli NO hace

Para que quede explícito, Milli **no**:

- recopila ni transmite tus datos personales o financieros hacia nosotros
- usa servicios de análisis, informes de errores o telemetría
- incluye publicidad ni identificadores publicitarios
- te rastrea entre apps o sitios web, ni comparte datos con brokers de datos
- crea cuentas de usuario, ni requiere un correo electrónico, número de
  teléfono o inicio de sesión
- lee datos de salud, actividad física o ubicación de tu iPhone o Apple
  Watch
- envía tus datos a ningún servicio de IA, ni los usa para entrenar modelos
  de aprendizaje automático — el Smart Chat se ejecuta por completo en tu
  dispositivo

La etiqueta de privacidad de la App Store de Milli refleja esto: **Data Not
Collected (datos no recopilados)**.

## Comunicaciones de soporte

Si nos escribes por correo electrónico para pedir soporte, recibimos tu
dirección de correo, tu mensaje y cualquier información sobre el
dispositivo, la versión de la app, captura de pantalla u otro dato que
decidas incluir. La usamos únicamente para responder, investigar el problema
y mejorar Milli. No nos envíes tu libro contable, extractos u otros
registros financieros — no los necesitamos para responder una pregunta de
soporte.

Cuando se aplica el RGPD o el RGPD del Reino Unido, gestionamos el correo de
soporte sobre la base de nuestro interés legítimo en responder a quienes nos
escriben y en solucionar los problemas que reportan. No hay ningún otro
tratamiento para el que buscar una base, porque Milli no nos envía nada por
sí sola.

El correo de soporte es opcional y ocurre fuera de Milli. Lo procesan tu
proveedor de correo electrónico y Google, que aloja nuestro buzón de
soporte, según la
[Google Privacy Policy](https://policies.google.com/privacy). Los
servidores de correo de Google están ubicados en Estados Unidos, por lo que
un mensaje de soporte que nos envíes se procesa allí. Conservamos los
mensajes de soporte hasta 24 meses, y más tiempo solo cuando una obligación
legal, de seguridad o de conservación de registros lo exija. Puedes
solicitarnos que eliminemos tu correspondencia de soporte escribiendo a la
dirección de abajo.

## Conservación y eliminación de datos

Milli no nos envía nada, así que no conservamos ninguno de tus datos
financieros y no tenemos nada que conservar ni eliminar. La única excepción
es el correo de soporte que decidas enviarnos, tratado más arriba.

- **Para eliminar los datos locales:** elimina la app de tu dispositivo, o
  usa las propias opciones de restablecer/eliminar de la app.
- **Para eliminar los datos de tu Apple Watch:** elimina Milli del reloj,
  como se describe en la sección de Apple Watch más arriba.
- **Para eliminar los datos sincronizados:** desactiva la sincronización con
  iCloud y elimina los datos de la app en **Ajustes → tu nombre → iCloud →
  Administrar almacenamiento de la cuenta**.

Eliminar la app no elimina automáticamente los datos ya sincronizados con tu
cuenta de iCloud; usa el paso anterior para eso. Eliminar la app del iPhone
también elimina su app complementaria del Apple Watch.

## Tus derechos

Según dónde vivas, puedes tener derechos en virtud del RGPD, el RGPD del
Reino Unido, la CCPA/CPRA u otras leyes similares — incluido el derecho a
acceder, corregir, exportar o eliminar tus datos personales, y el derecho a
no sufrir discriminación por ejercerlos.

Milli está diseñada para que ejerzas estos derechos directamente: tus datos
están en tu propio dispositivo y en tu propia cuenta de iCloud, bajo tu
control en todo momento. No conservamos ninguna copia, así que no podemos
producir, modificar ni borrar una en tu nombre. No vendemos ni compartimos
información personal, y nunca lo hemos hecho.

Si consideras que no hemos cumplido con nuestras obligaciones, puedes
contactarnos en la dirección de arriba, y tienes derecho a presentar una
reclamación ante tu autoridad local de protección de datos.

## Menores

Milli no está dirigida a menores y no recopila a sabiendas ninguna
información de nadie, incluidos los menores de 13 años (o la edad mínima
equivalente en tu país). Dado que la app no recopila ningún dato en
absoluto, no se nos puede transmitir dicha información.

## Cambios en esta política

Si esta política cambia, actualizaremos esta página y revisaremos la fecha
de "Última actualización" indicada arriba. Los cambios importantes también
se indicarán en las notas de la versión de la app. Te recomendamos revisar
esta página periódicamente.

## Contacto

Preguntas, inquietudes o solicitudes:

**ivnsjdev@gmail.com**
