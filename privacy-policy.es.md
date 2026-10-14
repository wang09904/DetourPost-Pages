# Política de privacidad de Detour Post

**Borrador de revisión interna · actualizado el 6 de octubre de 2026 · no publicado ni vigente · revisión jurídica y lingüística en curso.**

---

## 1. Introducción

Detour Post está operada por Yong Wang, una persona física. En esta política, «nosotros» se refiere a Yong Wang, quien determina cómo se tratan los datos personales para el servicio.

Esta Política de Privacidad explica qué información recopilamos, por qué la procesamos, cómo se maneja y almacena, los períodos de retención y cómo puedes ejercer tus derechos de privacidad.

Nuestro principio fundamental es sencillo: **Tus cartas son privadas entre tú y el destinatario que eliges. No podemos leerlas ni tenemos intención de leerlas.**

## 2. Información que procesamos

### 2.1 Información que proporcionas activamente

| Información | Detalles | Necesidad |
|---|---|---|
| Cuenta e identidad de inicio de sesión | Identificador de cuenta, identificador del proveedor de inicio de sesión y correo electrónico verificado devueltos por Apple o Google | Necesarios para crear y autenticar la cuenta |
| Credenciales de acceso | Tokens de sesión; el servicio guarda un hash de cada token | Necesarios para un acceso seguro |
| Mes y año de nacimiento y región seleccionada | La app comprueba en tu dispositivo la edad aplicable según el mes y año que indicas y la región elegida | Necesarios para registrarte. El mes y el año de nacimiento se guardan en los datos de la app asociados a tu cuenta en tu dispositivo, donde puedes consultarlos y modificarlos; el mes y el año de nacimiento no se envían ni se almacenan en nuestros servidores. El servicio conserva por separado la versión de la regla aplicada y la región de inicio de sesión |
| Nombre para mostrar | Nombre que ven las personas con las que intercambias cartas | Obligatorio para completar el registro; puedes cambiarlo después en el perfil |
| Ciudad | Ciudad elegida para enviar cartas, incluidos los datos del lugar guardados por la Aplicación | Obligatoria para completar el registro y enviar cartas |
| Información de conexión | Estado de la relación, códigos de invitación y códigos secretos para recibir cartas | Necesaria para intercambiar cartas |
| Contenido de las cartas | Texto, papel de carta y decoraciones elegidos, fotos adjuntas, mensajero y hora de entrega elegida o programada | Se genera solo cuando eliges enviar una carta |
| Datos de la denuncia | Para denunciar debes escribir una descripción y elegir de 1 a 3 capturas. Tratamos estos materiales, tus aclaraciones o apelaciones y los identificadores de cuenta y caso asociados para investigar y resolver la denuncia. No obtenemos automáticamente la carta original, sus fotos adjuntas originales ni las claves de descifrado. | Se genera solo cuando presentas una denuncia |
| Notas privadas | Notas que escribes sobre un contacto | Opcionales. Se guardan en tu dispositivo y se incluyen en tu copia personal de iCloud solo si la activas; no se suben a nuestro servicio |

**Cifrado de extremo a extremo de cartas y fotos.** El texto y las fotos se cifran en tu dispositivo antes de enviarse a nuestro servicio. Para esos contenidos conservamos texto cifrado, sin claves de descifrado. Los demás datos de la cuenta y del servicio descritos aquí se tratan por separado. Consulta la sección 4.

### 2.2 Información generada automáticamente durante el uso

| Información | Detalles | Propósito |
|---|---|---|
| Estado de entrega | Salida, hitos del viaje, llegada, retiro, estado de terminación | Envío y entrega de cartas |
| Estado de cuenta y seguridad | Estado de cuenta, listas de bloqueo recíproco, estado de manejo de informes | Administración de cuentas y prevención de abusos |
| Registro de compras e inventario | Pedidos, movimientos y saldo de monedas, existencias de sellos y unidades de programación de entrega, propiedad de artículos permanentes, suscripciones y estado de restauración de compras | Facturación, prestación, restauración y reembolsos |
| Tokens del dispositivo y de notificaciones push | Tokens de notificaciones push de dispositivos y metadatos necesarios | Envío de notificaciones de estado de cartas |
| Registros de servicio | Registros operativos de API, seguimiento de errores y diagnóstico de rendimiento | Seguridad, estabilidad y resolución de problemas |

**Notificaciones push.** El aviso visible usa texto genérico. La carga también incluye una categoría de notificación y un identificador de evento opaco para abrir la pantalla correspondiente; no contiene texto de cartas, fotos ni ubicación. Los registros operativos pueden contener detalles técnicos de solicitudes o errores; consulta la sección 8.

### 2.3 Lo que NUNCA hacemos

- NO accedemos a tu fototeca completa, a tus contactos ni a tu ubicación GPS precisa;

- La app no usa identificadores publicitarios (IDFA/IDFV) para orientar anuncios ni para el seguimiento entre apps, y no incluye un SDK publicitario.

- No usamos datos de cartas para entrenar modelos de IA: no tenemos acceso al texto sin cifrar;

- NUNCA vendemos tu información personal a terceros.

## 3. Por qué procesamos la información

| Finalidad | Información utilizada |
|---|---|
| Enviar y recibir cartas | ID de cuenta, nombre visible, ciudad, datos de conexión, carta cifrada y estado de entrega |
| Compras integradas, prestación y reembolsos | Registros de compras y activos, y estado de la membresía |
| Avisos de entrega | Token de notificaciones push y estado de entrega |
| Seguridad, denuncias y prevención de abusos | Estado de seguridad y de la cuenta, datos de denuncias y registros operativos |
| Diagnóstico y estabilidad | Registros operativos |
| Solicitudes sobre derechos y reclamaciones | Información que nos proporcionas |

La base jurídica de cada tratamiento depende de la legislación aplicable y de las circunstancias concretas. Este borrador todavía no asigna una base jurídica a cada finalidad. Esa revisión debe completarse antes de publicar la política; no nos basaremos en una base que no sea aplicable según la legislación correspondiente.

## 4. Cifrado de extremo a extremo

Esta es la salvaguardia técnica más importante de Detour Post:

**El cifrado se realiza en tu dispositivo.** Cuando tocas «Sellar esta carta», todo el texto y las fotos se cifran en tu dispositivo antes de transmitirse. Solo tú y el destinatario que designas tienen las claves de descifrado.

**Guardamos el texto y las fotos de las cartas únicamente cifrados.** No tenemos las claves para descifrarlos ni ofrecemos recuperación manual de claves. También tratamos los datos de la cuenta y del servicio descritos en esta Política.

**Sin excepciones.** No mantenemos puertas traseras administrativas, canales de inspección de contenido ni excepciones que permitan al servicio de atención al cliente acceder al contenido. Debido a que no podemos ver texto sin formato, no podemos realizar filtrado automático de palabras clave ni recomendación de contenido.

- Solo tú puedes ver el contenido antes de la entrega;

- Solo tú y tu destinatario podrán ver el contenido después de la entrega;

- Si pierdes tu dispositivo y no tienes una copia de seguridad personal en iCloud, no podemos recuperar tus cartas: no tenemos las claves;

- Al enviarla se bloquea el contacto en ambos sentidos y se detienen las cartas de esta persona que aún no te hayan llegado. Las cartas entregadas no cambian. Para denunciar debes escribir una descripción y elegir de 1 a 3 capturas. Tratamos estos materiales, tus aclaraciones o apelaciones y los identificadores de cuenta y caso asociados para investigar y resolver la denuncia. No obtenemos automáticamente la carta original, sus fotos adjuntas originales ni las claves de descifrado. Las denuncias generan un recordatorio al operador, sin prometer un plazo concreto de revisión o respuesta.

**Copia de seguridad personal.** Si la activas, los datos seleccionados de tu bolsa postal —incluidas notas privadas de contactos, borradores, materiales de invitaciones pendientes y cartas guardadas— se cifran en tu dispositivo y se copian en tu iCloud personal mediante CloudKit. La clave de la copia se guarda en el Llavero del dispositivo. Una vez verificada una copia, se guarda una clave de recuperación en el Llavero de iCloud para que pueda estar disponible en tus otros dispositivos Apple. No recibimos ninguna de las dos claves ni podemos descifrar la copia.

## 5. Permisos del sistema

La Aplicación puede solicitar permiso para notificaciones después de que envíes o recibas tu primera carta; también puedes solicitarlo en Ajustes. Si decides guardar una tarjeta de viajero generada en tu fototeca, solicita permiso para añadir fotos únicamente.

| Permiso | Cuando se solicita | Propósito |
|---|---|---|
| Notificaciones | Después de la primera carta enviada o recibida, o al activarlas en Ajustes | Aviso visible genérico; la carga incluye una categoría y un identificador de evento opaco para abrir la pantalla correspondiente, sin texto de cartas ni ubicación |
| Fotos (solo añadir) | Cuando eliges guardar una tarjeta de viajero generada | Guarda esa imagen; no permite explorar tu fototeca |

La Aplicación sincroniza tus preferencias de notificaciones con el servicio, que las usa para decidir qué avisos enviar. El permiso de iOS controla si pueden mostrarse en el dispositivo. Ninguna de estas acciones elimina ni desactiva por sí sola el token del dispositivo en el servicio. Rechazar un permiso opcional no impide por sí solo el envío o la recepción básicos.

**Otros usos de permisos:**

- **Fotos:** Al adjuntar una foto, el selector del sistema entrega a la Aplicación solo la imagen elegida; no se explora toda tu fototeca. Guardar una tarjeta de viajero generada utiliza el permiso independiente para añadir fotos y su aviso del sistema.

- **Ubicación:** Tú eliges la ciudad de cada carta. No recopilamos la ubicación del dispositivo ni seguimos tus desplazamientos. La app incluye un catálogo limitado de nombres y coordenadas de países y ciudades para sugerencias de búsqueda locales, resultados sin conexión limitados y etiquetas del mapa. Primero consulta ese catálogo; si encuentra una ciudad, la usa localmente y no envía el término de búsqueda a MapKit. Si no encuentra resultados, solicita lugares a Apple MapKit. Cuando el catálogo no contiene el centro de un país o región seleccionados, la app puede enviar su nombre a Apple mediante Core Location para centrar el mapa. La app también usa Core Location para obtener información de un punto elegido en el mapa. Si Apple no devuelve resultados, puede recurrir de forma limitada a una ciudad cercana del catálogo. Apple recibe el texto de búsqueda, el nombre del país o región o las coordenadas del punto que corresponda. Estas funciones no requieren permiso de ubicación.

- **Contactos, cámara, micrófono, seguimiento de aplicaciones (ATT):** No solicitado y no existe el código correspondiente.

## 6. Terceros

No vendemos información personal. Los proveedores necesarios para las funciones que utilizas tratan los datos correspondientes. Para el almacenamiento y tratamiento en los servidores del servicio del texto y las fotos de las cartas, reciben datos cifrados; no les proporcionamos claves de descifrado.

| Terceros | Datos procesados ​​ | Propósito | Notas |
|---|---|---|---|
| Apple | Identificador de inicio de sesión y correo verificado, compras y suscripciones dentro de la app, token y entrega de notificaciones push, copias cifradas del archivo personal en iCloud y claves de recuperación si activas la copia, términos enviados en búsquedas de lugares con MapKit, nombres de países o regiones enviados para centrar el mapa cuando el catálogo no tiene un centro, y coordenadas de puntos del mapa enviadas para la geocodificación inversa de Core Location | Inicio de sesión, pagos, avisos, copias de seguridad y funciones de mapas y búsqueda | Se aplica la [Política de privacidad de Apple](https://www.apple.com/legal/privacy/) |
| Google | Identificador del proveedor de inicio de sesión y correo electrónico verificado, cuando se facilita | Autenticación cuando eliges Google | Se aplica la [Política de privacidad de Google](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Token push, aviso genérico, categoría de notificación e identificador de evento opaco | Envío de notificaciones | La carga no contiene texto de cartas, fotos ni ubicación precisa |
| Cloudflare | Cartas cifradas, registros de cuenta y acceso, datos de la ciudad elegida, compras y envíos, tokens push y registros del servicio | Computación en la nube, base de datos y almacenamiento de objetos | Se aplica la [Política de privacidad de Cloudflare](https://www.cloudflare.com/privacypolicy/) |

La aplicación para iOS no contiene SDK de seguimiento, publicidad o análisis de terceros.

## 7. Almacenamiento de datos y transferencias internacionales

- **En tu dispositivo:** Cartas, borradores, notas privadas de contactos y preferencias.

- **En tu iCloud personal:** Si la activas, una copia cifrada de los datos seleccionados de tu bolsa postal, incluidas notas privadas de contactos, borradores, materiales de invitaciones pendientes y cartas guardadas.

- **En nuestros servidores:** Identificadores de cuenta y acceso, correo verificado, nombres para mostrar, datos guardados de la ciudad elegida, relaciones y estado de entrega, cartas cifradas, compras, tokens push y registros del servicio. La infraestructura está fuera de los países o regiones de algunos usuarios, por lo que estos datos pueden tratarse internacionalmente.

## 8. Períodos de retención de datos

| Información | Plazo de conservación |
|---|---|
| Mes y año de nacimiento | El mes y el año de nacimiento se guardan en los datos de la app asociados a tu cuenta en tu dispositivo, donde puedes consultarlos y modificarlos; el mes y el año de nacimiento no se envían ni se almacenan en nuestros servidores |
| Cuenta e identidad de inicio de sesión | Al eliminar la cuenta, se desactiva, se revocan las sesiones y se eliminan los datos del perfil y de notificaciones. El diseño actual conserva el registro de la cuenta eliminada y el identificador del proveedor de inicio de sesión; aún no se ha fijado un plazo de eliminación. |
| Contenido cifrado de las cartas | La limpieza del contenido cifrado del servidor comienza cuando el dispositivo destinatario confirma que guardó la carta completa. Si no hay confirmación, la carta deja de estar disponible 90 días después de que la carta esté disponible para el destinatario (en cartas programadas, desde la hora prevista) y pasa al proceso de limpieza. El vencimiento de este plazo no restablece la cuenta eliminada del remitente. |
| Registros de compra y prestación | Se conservan para gestionar compras, reembolsos y entregas ya iniciadas. Aún no se ha definido un plazo fijo. |
| Tokens de notificaciones push | Las preferencias de la app determinan qué avisos se envían; el permiso de iOS controla si se muestran en el dispositivo. Al eliminar la cuenta se elimina el token del dispositivo; los tokens que APNs marque como inválidos se desactivan. |
| Denuncias de seguridad | La descripción, las capturas, las aclaraciones o apelaciones y los datos identificables del caso se eliminan 90 días después del cierre definitivo. Si una apelación válida reabre el caso, el plazo vuelve a empezar con el nuevo cierre definitivo. Las capturas no adjuntadas a una denuncia enviada se eliminan tras un día. Una restricción activa conserva solo la decisión mínima necesaria para aplicarla, revisarla y apelarla. Tras eliminar el caso original, aún puedes apelar por correo a soporte indicando el identificador de restricción; el operador puede levantarla desde la lista de cuentas restringidas. |
| Registros del servicio | Pueden generarse por seguridad, fiabilidad y diagnóstico, e incluir detalles técnicos de solicitudes o errores. Aún no se ha definido un plazo fijo. |

Todavía no se han definido los plazos o criterios de eliminación de los registros de cuentas eliminadas e identidades de proveedores, compras y prestación, denuncias de seguridad y registros del servicio. Estas reglas y la base jurídica de cada finalidad deben revisarse antes de publicar la política.

## 9. Tus derechos de privacidad

Según dónde residas, la legislación aplicable puede concederte derechos de acceso, rectificación, supresión o copia de información personal, oposición o limitación de ciertos tratamientos y retirada del consentimiento. Esta Política no limita los derechos que te correspondan por ley. Envía las solicitudes a detourpost@aivolo.studio; podemos pedirte la información necesaria para verificar tu identidad.

| Derecho | Cómo ejercerlo |
|---|---|
| Acceso o copia | Abre «Yo» para ver los datos de la cuenta, las compras y los artículos; contacta con nosotros para solicitudes no disponibles en la Aplicación |
| Rectificación | Abre «Yo» → «Perfil» para cambiar tu nombre para mostrar y ciudad; contacta con nosotros sobre otros datos |
| Eliminación | Utiliza la función «Eliminar cuenta» de la Aplicación o contacta con nosotros para solicitar la eliminación de datos específicos. |
| Retirada del consentimiento | Escribe a detourpost@aivolo.studio para retirar el consentimiento de un tratamiento que se base en él; la legislación aplicable determina el efecto sobre el tratamiento anterior |
| Eliminación de la cuenta | «Yo» → «Eliminar cuenta» → «Eliminar cuenta» |
| Preguntas y consultas | Contacto detourpost@aivolo.studio |

**Al eliminar la cuenta:** Se desactiva la cuenta, se revocan sus sesiones y se eliminan los datos de perfil y notificaciones. Los envíos que aún no hayan partido se cancelan; las cartas ya en camino siguen el plan establecido. Eliminar la cuenta de la Aplicación no cancela una membresía facturada por Apple; gestiónala o cancélala en los ajustes de suscripciones de tu cuenta Apple. El diseño actual conserva un registro de la cuenta eliminada y la identidad del proveedor de acceso; consulta la sección 8.

Tramitaremos las solicitudes conforme a la legislación aplicable. El plazo dependerá de la naturaleza de la solicitud; no prometemos un plazo general.

## 10. Menores

La app está dirigida a personas que cumplen la edad mínima aplicable, que es de al menos 16 años (15 años en Corea) y puede variar en algunas regiones. Durante el registro, la app comprueba en tu dispositivo, según el mes y año de nacimiento que indicas y la región elegida, si cumples el requisito de edad correspondiente. El mes y año se guardan en los datos de la app de tu dispositivo y no se envían ni se almacenan en nuestros servidores.

Si crees que alguien podría no tener la edad mínima aplicable, escribe a detourpost@aivolo.studio. Si Yong Wang llega a tener conocimiento del caso, hará esfuerzos razonables por revisarlo y tomar las medidas que exija la legislación aplicable. No se promete un plazo fijo de revisión o respuesta. Las personas tutoras también pueden escribir a esa dirección.

## 11. Medidas de seguridad

- Cifrado de extremo a extremo para texto de cartas y fotografías;

- Canales de transporte cifrados (TLS/HTTPS);

- Credenciales y claves almacenadas en un sistema de almacenamiento seguro (Llavero iOS);

- Protección del dispositivo para las credenciales y claves de cifrado guardadas localmente.

Ninguna medida garantiza una seguridad absoluta. Si ocurre un incidente de seguridad de datos, notificaremos y adoptaremos las medidas exigidas por la legislación aplicable.

## 12. Actualizaciones de políticas

Podemos actualizar esta Política. El texto actual y la fecha de actualización aparecerán en esta página. No utilizaremos información personal para fines incompatibles con los descritos aquí. Si la legislación aplicable exige informar de un cambio importante o un nuevo uso de los datos, lo haremos por un medio adecuado.

## 13. Contacto y reclamaciones

- **Operador:** Yong Wang

- **Correo electrónico:** detourpost@aivolo.studio

Para preguntas o reclamaciones, escribe a detourpost@aivolo.studio. Si Yong Wang tiene conocimiento del mensaje, hará esfuerzos razonables por revisarlo y responder cuando corresponda. No se promete un plazo concreto. También puedes presentar una reclamación ante una autoridad de control competente para tu asunto.
