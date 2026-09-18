# 

**Implicaciones:**

---

## 1. Introducción

Detour Post (en adelante, "la Aplicación") es operada por Yong Wang (en adelante, "nosotros", "nos" o "nuestro"). Actuamos como controlador de datos de su información personal.

Esta Política de Privacidad explica qué información recopilamos, por qué la procesamos, cómo se maneja y almacena, los períodos de retención y cómo puede ejercer sus derechos de privacidad.

Nuestro principio fundamental es sencillo: **Sus cartas son privadas entre usted y su destinatario. No podemos leerlos y no tenemos intención de leerlos.**

## 2. Información que procesamos

### 2.1 Información que usted proporciona activamente

| Información | Detalles | Necesidad |

|---|---|---|

| Identificador de cuenta | Identificador único obtenido mediante Iniciar sesión con Apple o Google | Requerido para la creación de cuenta |

| Credenciales de inicio de sesión | Tokens de autenticación de sesión | Requerido para acceso seguro |

| Fecha de nacimiento y región | Se utiliza en el registro únicamente para determinar la elegibilidad por edad | Requerido para el registro. **La fecha de nacimiento se utiliza únicamente en el momento de la evaluación y se descarta inmediatamente; nunca lo almacenamos.** Solo se conservan la versión de la regla y la región seleccionada |

| Nombre para mostrar | Nombre personalizado establecido en su perfil, visible para sus destinatarios | Opcional |

| Ciudad | Ciudad seleccionada como punto de salida/llegada | Opcional, pero obligatorio para enviar cartas |

| Información de conexión | Estado de la relación, códigos de invitación y secretos de reclamo | Obligado a intercambiar cartas |

| Contenido de la carta | Texto de carta, elección de papel de carta y decoraciones, fotografías adjuntas, mensajería, hora de llegada | Creado solo cuando eliges enviar |

| Detalles del informe | Categoría de infracción seleccionada (acoso, spam, seguridad) e ID del objetivo. **NO contiene texto de letras, fotografías, texto de forma libre ni coordenadas**; bloquea automáticamente el partido simultáneamente | Creado solo cuando presenta un informe |

| Notas privadas | Notas privadas que asignas a un contacto | Opcional. **Almacenado estrictamente en su dispositivo local, nunca cargado** |

**Cifrado de extremo a extremo de cartas y fotos.** El texto de las cartas y las fotos se cifran directamente en su dispositivo local antes de su transmisión. Sólo tenemos texto cifrado y no poseemos claves de descifrado. En consecuencia, **no podemos leer, inspeccionar ni proporcionar el texto o las fotografías de su carta a nadie**, incluidas las consultas policiales, donde solo se puede proporcionar texto cifrado. Consulte la Sección 4.

### 2.2 Información generada automáticamente durante el uso

| Información | Detalles | Propósito |

|---|---|---|

| Estado de entrega | Salida, hitos del viaje, llegada, retiro, estado de terminación | Impulsando el canal de entrega postal |

| Estado de cuenta y seguridad | Estado de cuenta, listas de bloqueo recíproco, estado de manejo de informes | Administración de cuentas y prevención de abusos |

| Libro mayor de comercio | Registros de pedidos, saldos de monedas, propiedad permanente de artículos, suscripciones activas | Facturación, cumplimiento y manejo de reembolsos |

| Fichas de dispositivo y push | Tokens de inserción de dispositivos y metadatos necesarios | Envío de notificaciones de estado de cartas |

| Registros de servicio | Registros operativos de API, seguimiento de errores y diagnóstico de rendimiento | Seguridad, estabilidad y resolución de problemas |

**Sin secretos en registros ni notificaciones automáticas.** Los registros operativos nunca contienen texto de letras, fotografías, códigos de invitación ni coordenadas exactas. Las notificaciones push solo contienen frases de estado genéricas (por ejemplo, "Ha llegado una carta") sin identificadores personales, texto del mensaje ni ciudades.

### 2.3 Lo que NUNCA hacemos

- NO accedemos a su biblioteca de fotos completa, contactos ni ubicación GPS precisa;

- NO recopilamos identificadores de seguimiento (IDFA/IDFV), no incorporamos SDK de anuncios ni realizamos seguimiento entre aplicaciones;

- NO introducimos datos de letras en modelos de entrenamiento de IA; no tenemos acceso a texto sin formato;

- NUNCA vendemos su información personal a terceros.

## 3. Por qué procesamos la información

| Propósito | Información involucrada | Base Legal |

|---|---|---|

| Entrega y recepción postal | ID de cuenta, nombre para mostrar, ciudad, información de conexión, carta cifrada, estado de entrega | Ejecución del contrato de servicios |

| Compras y reembolsos desde la aplicación | Libro de compras, validez de la suscripción | Ejecución del contrato de servicios |

| Notificaciones push de entrega | Token de inserción, estado de entrega | Su consentimiento (revocable en cualquier momento) |

| Seguridad, prevención de abusos e informes | Estado de seguridad, detalles del informe, registros operativos | Interés legítimo y obligación legal |

| Diagnóstico y estabilidad del servicio | Registros operativos | Interés legítimo |

| Gestión de derechos y consultas de los usuarios | Información proporcionada por usted | Obligación legal |

## 4. Cifrado de extremo a extremo

Esta es la salvaguardia técnica más importante de Detour Post:

**El cifrado se produce localmente en su dispositivo.** Cuando toca "Sellar esta carta", todo el texto y las fotos se cifran en su dispositivo antes de la transmisión. Las claves de descifrado las poseen exclusivamente usted y su destinatario designado.

**Solo conservamos texto cifrado.** Nuestros servidores solo almacenan blobs cifrados. No conservamos claves de descifrado de ninguna forma ni proporcionamos recuperación manual de claves.

**Sin excepciones.** No mantenemos puertas traseras administrativas, canales de inspección de contenido ni anulaciones de servicio al cliente. Debido a que no podemos ver texto sin formato, no podemos realizar filtrado automático de palabras clave ni recomendación de contenido.

- Sólo usted puede ver el contenido antes de la entrega;

- Sólo usted y su destinatario podrán ver el contenido después de la entrega;

- Si pierde su dispositivo y no tiene una copia de seguridad personal de iCloud, no podemos recuperar sus cartas: no tenemos las claves;

- Los informes de seguridad activan bloqueos de relaciones y penalizaciones de cuentas, sin que operadores humanos lean el contenido de las cartas.

**Copia de seguridad personal.** Las copias de seguridad de los datos de las cartas se realizan exclusivamente a través de tu iCloud personal si está habilitado. Las copias de seguridad residen completamente dentro de su ecosistema de ID de Apple. No tenemos acceso a su copia de seguridad de iCloud ni a sus claves de llavero.

## 5. Permisos del sistema

La aplicación solicita sólo un permiso del sistema:

| Permiso | Cuando se solicita | Propósito |

|---|---|---|

| Notificaciones | Cuando opta por recibir alertas de cartas | Le avisa cuando salen o llegan cartas. Las cargas útiles contienen sólo frases genéricas |

Deshabilitar las notificaciones no afecta el envío o la recepción de cartas.

**Permisos que NO solicitamos:**

- **Fotos:** La selección de fotos utiliza el selector de fotos del sistema nativo. Solo la imagen seleccionada se pasa a la aplicación; No se solicita ni se requiere acceso completo a la biblioteca de fotografías.

- **Ubicación:** Las ciudades se seleccionan manualmente de una lista. Nunca rastreamos las coordenadas de su dispositivo.

- **Contactos, cámara, micrófono, seguimiento de aplicaciones (ATT):** No solicitado y no existe el código correspondiente.

## 6. Terceros

Nunca vendemos datos personales. La información se comparte estrictamente con los proveedores de infraestructura necesarios:

| Terceros | Datos procesados ​​ | Propósito | Notas |

|---|---|---|---|

| manzana | ID de cuenta, compras de StoreKit, envío push, codificación geográfica de MapKit | Autenticación, facturación en la aplicación, notificaciones, visualización de mapas | Sujeto a la [Política de privacidad de Apple](https://www.apple.com/legal/privacy/) |

| Google | ID de cuenta | Autenticación opcional | Sujeto a la [Política de Privacidad de Google](https://policies.google.com/privacy) |

| Servicio de notificaciones push de Apple (APN) | Token de inserción, carga útil de alerta genérica | Envío de notificación | Las cargas útiles no contienen texto de letra ni identidades de destinatarios |

| Proveedores de infraestructura en la nube | Blobs de cartas cifradas, libro de cuentas | Computación en la nube y almacenamiento seguro | Procesado estrictamente bajo nuestras instrucciones |

La aplicación para iOS no contiene SDK de seguimiento, publicidad o análisis de terceros.

## 7. Almacenamiento de datos y transferencias internacionales

- **En su dispositivo:** Cartas, borradores y preferencias locales.

- **En tu iCloud personal:** Copias de seguridad de bases de datos cifradas dentro de tu cuenta privada de Apple.

- **En nuestros servidores:** ID de cuentas, nombres para mostrar, cargas útiles de cartas cifradas y libros de transacciones almacenados en una infraestructura segura en la nube en el extranjero. Los datos pueden transferirse y procesarse internacionalmente bajo estrictas salvaguardias contractuales.

## 8. Períodos de retención de datos

| Información | Período de retención |

|---|---|

| Fecha de nacimiento | No almacenado. Evaluado una vez en el momento del registro y descartado inmediatamente |

| ID de cuenta, nombre para mostrar, ciudad, conexiones | Duración del ciclo de vida de la cuenta; eliminado o anonimizado irreversiblemente tras la eliminación de la cuenta |

| Texto cifrado de letras | Eliminado inmediatamente después de la confirmación de la entrega por parte del destinatario; cartas no reclamadas limpiadas después de 90 días |

| Libro mayor de compras | Retenido según lo exigen las leyes financieras, fiscales y de protección al consumidor |

| Fichas de empuje | Eliminado de los servidores inmediatamente después de la notificación de exclusión voluntaria o eliminación de la cuenta |

| Registros de servicio | Se conserva durante un breve período de diagnóstico y se elimina automáticamente. No contiene secretos privados |

## 9. Sus derechos de privacidad

Puede ejercer los siguientes derechos con respecto a su información personal:

| Derecha | Cómo hacer ejercicio |

|---|---|

| Acceso y portabilidad | Ver perfil, compras y activos en "Mi perfil"; solicitar exportación a través de detourpost@aivolo.studio |

| Rectificación | Edite el nombre para mostrar y la ciudad en Configuración del perfil; contáctenos para otros registros |

| Eliminación | Utilice la función "Eliminar cuenta" en la aplicación o contáctenos para solicitudes de datos específicas |

| Retirar el consentimiento | Desactive las notificaciones en Configuración de la aplicación o Configuración del sistema iOS |

| Eliminación de cuenta | Navegue a "Mi perfil" → "Eliminación y aislamiento de cuenta" → "Eliminar cuenta" |

| Preguntas y consultas | Contacto detourpost@aivolo.studio |

**Qué sucede al eliminar la cuenta:** Las cartas no enviadas se cancelan; las cartas partidas continúan hasta su destino; Los registros de perfil, las relaciones de bloques y los tokens de dispositivos se borran de forma inmediata y permanente.

Respondemos a todas las solicitudes de privacidad dentro de **48 horas**.

## 10. Menores

La aplicación está destinada a usuarios mayores de 13 años (o más, según los requisitos de la jurisdicción local). No recopilamos intencionalmente datos personales de menores menores de la edad de registro aplicable. Si cree que un menor se ha registrado sin autorización, comuníquese con detourpost@aivolo.studio y eliminaremos la cuenta de inmediato.

## 11. Medidas de seguridad

- Cifrado de extremo a extremo para texto de cartas y fotografías;

- Canales de transporte cifrados (TLS/HTTPS);

- Credenciales y claves almacenadas en un sistema de almacenamiento seguro (Llavero iOS);

- Principio de privilegio mínimo para la infraestructura del servidor;

- Escaneo continuo de vulnerabilidades y auditorías de configuración.

## 12. Actualizaciones de políticas

Podemos actualizar esta Política de Privacidad periódicamente. Los cambios importantes se notificarán de forma destacada dentro de la aplicación. Si no está de acuerdo con los términos modificados, puede eliminar su cuenta.

## 13. Contáctenos y quejas

- **Operador:** Yong Wang

- **Correo electrónico:** detourpost@aivolo.studio

Respondemos a las consultas dentro de **48 horas**. También tiene derecho a presentar una queja ante la autoridad supervisora ​​de protección de datos local.

© 2026 Yong Wang. Reservados todos los derechos.

---

© 2026 Yong Wang. All rights reserved.
