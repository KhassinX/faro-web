---
layout: prose
title: Política de Privacidad
permalink: /es/legal/privacy/
lang: es
canonical_en: /legal/privacy/
canonical_es: /es/legal/privacy/
redirect_from:
  - /es/privacidad
  - /es/privacidad/
updated: 2026-06-12
---

# Política de Privacidad — Faro

**Fecha de vigencia**: 2026-06-12
**App**: Faro
**Responsable del tratamiento**: KHASSINX LLC, una sociedad de responsabilidad limitada de Florida (Estados Unidos)
**Contacto**: legal@khassinx.com

---

## Resumen

Faro es un espacio privado y cifrado de extremo a extremo donde un adulto de confianza y un niño o niña siguen cerca a la distancia. **No recopilamos tus datos.** Tus mensajes, dibujos, recuerdos y llamadas se sellan de extremo a extremo y viven solo en tus dispositivos y en tu propio iCloud — controlado por tu Apple ID, no por nosotros. No tenemos ningún servidor con el contenido de tu familia, ni publicidad, ni analytics, ni trackers. No hay nada que vender, porque no hay nada recopilado.

Puedes reportar o bloquear un contacto desde dentro de la app, y puedes acceder, exportar o borrar tus datos cuando quieras.

---

## Qué recopilamos

**Nada.** La etiqueta de privacidad de Faro en el App Store es **Datos no recopilados** — la más fuerte que ofrece Apple, y una etiqueta honesta.

| Categoría | ¿La recopilamos? |
|---|---|
| Mensajes, dibujos, cápsulas del tiempo, recuerdos | ❌ No — cifrados de extremo a extremo, en tus dispositivos + tu iCloud |
| Actividad o comportamiento de tu hijo o hija | ❌ No — Faro nunca crea un perfil de un niño |
| Contactos / Fotos / Micrófono / Cámara | ❌ No (se usan solo en el dispositivo con tu permiso, nunca llegan a nosotros) |
| Ubicación | ❌ No |
| Identificadores publicitarios (IDFA) | ❌ No |
| Analytics de uso | ❌ Cero SDKs de analytics |
| Informes de fallos | ❌ No |
| Correo electrónico | Solo si **tú** nos escribes — ver "Si nos escribes" más abajo |

El manifiesto `PrivacyInfo.xcprivacy` de la app declara lo mismo. Apple lo verifica durante la revisión.

## Dónde viven tus datos

Faro está construida para que el contenido de tu familia nunca llegue a un servidor que controlemos.

| Qué | Dónde |
|---|---|
| Mensajes, dibujos, cápsulas del tiempo, recuerdos, tu historial de actividad | En tu dispositivo + **tu iCloud personal** (cifrado por Apple, tu Apple ID) |
| Claves de cifrado | En el Secure Enclave de tu dispositivo y en el Llavero de iCloud — nunca se exportan a nosotros |
| Material del vínculo / emparejamiento | Se intercambia cifrado de extremo a extremo entre los dos dispositivos; nunca vemos las claves |

La sincronización de iCloud usa **tu** Apple ID. Nunca lo vemos, accedemos ni tenemos forma de recuperarlo. Apple lo cifra en tránsito y en reposo, y de extremo a extremo cuando tienes activada la Protección de Datos Avanzada. Si borras la app y eliminas sus datos de iCloud, tu copia desaparece — y no hay otra copia en ningún servidor, porque **no tenemos un servidor que guarde tu contenido.**

## Cifrado de extremo a extremo

Todo lo que tú y tu hijo o hija comparten en Faro está **cifrado de extremo a extremo**. El contenido se sella en el dispositivo que envía y solo se puede abrir en el dispositivo del vínculo verificado del otro lado.

- El otro padre, madre u hogar **no puede** leer un vínculo que no es el suyo — no como una regla, sino por diseño: las claves simplemente no existen en ningún lugar al que pueda llegar.
- **Nosotros tampoco** podemos leer tu contenido. No tenemos claves ni copias.
- Las llamadas usan **FaceTime de Apple**, cifrado de extremo a extremo por Apple. Faro nunca graba el audio ni el video de una llamada.

## Cómo se crean los vínculos (y cómo se mantienen seguros)

Un adulto configura cada vínculo. Para conectar el dispositivo de un adulto con el de un niño entre dos cuentas Apple distintas, Faro usa una invitación más un paso de verificación fuera de banda: ambas pantallas muestran una secuencia corta de símbolos, y el adulto y el niño confirman que coinciden — normalmente en una llamada juntos. Esto frena la suplantación y confirma que las dos personas son quienes dicen ser. No interviene ningún tercero, y la verificación ocurre directamente entre el adulto y el niño.

## Inteligencia en el dispositivo (Apple Intelligence)

Cuando tu dispositivo lo soporta, Faro usa **Apple Intelligence (Foundation Models)** para ayudar a un niño a expresarse, para redirigir con suavidad los temas sensibles hacia el adulto, y para escribir resúmenes semanales delicados para el adulto.

Este modelo corre **completamente en tu dispositivo**. Tus conversaciones nunca salen de tu iPhone, iPad o Mac para el procesamiento de IA. No enviamos tus datos a OpenAI, Anthropic, Google ni a ningún servicio de IA de terceros, y no tenemos un servidor de IA propio. En dispositivos sin Apple Intelligence, estas funciones se ocultan en silencio y el resto de Faro funciona normal.

## Consentimiento parental (privacidad de menores)

Faro siempre la configura un adulto, en nombre del niño o niña. El adulto que instala la app del niño y da el consentimiento debe atestiguar que es el **padre, la madre, el tutor legal o un adulto legalmente autorizado** del menor. Faro captura esa atestación durante la configuración.

Como un adulto configura y consiente cada vínculo, tratamos a **todo** niño o niña como que requiere consentimiento parental. Esto satisface la lectura más estricta de la ley de privacidad de menores — incluyendo **COPPA** (Estados Unidos) y **GDPR-K** (Unión Europea) — con un solo flujo consistente.

Nunca recopilamos a sabiendas datos personales directamente de un niño para nuestros propios fines. El contenido de un niño permanece dentro del vínculo cifrado, en sus dispositivos y en los del adulto.

## Suscripciones y compras

Si eliges un desbloqueo de pago o una suscripción opcional, lo procesa por completo **Apple StoreKit**. Recibimos solo una señal de Apple de que un Apple ID tiene un acceso activo — nunca tu nombre, método de pago ni dirección de facturación. Apple maneja todo eso. Gestiona o cancela cuando quieras en Ajustes → Apple ID → Suscripciones. Todas las funciones de seguridad y emergencia de Faro son gratuitas y nunca están detrás de un muro de pago.

## Notificaciones

Las notificaciones push son opt-in. Si las habilitas, tu dispositivo recibe un token de Apple Push Notification que solo se usa para entregar las señales que actives (un mensaje nuevo, una llamada entrante). No enviamos notificaciones de marketing. Faro no tiene lista de correo.

## Si nos escribes

Si escribes a cualquier dirección `@khassinx.com`, recibimos tu mensaje y tu dirección de respuesta vía nuestro proveedor de correo, y conservamos esa correspondencia para atender tu solicitud. No te agregamos a ninguna lista. Esa es la única situación en la que tenemos algún dato personal tuyo, y solo porque elegiste escribirnos.

## Tus derechos

Siempre tienes el control de tus datos:

- **Acceso** — tu contenido es visible en la app en todo momento.
- **Exportación** — exporta tus datos desde Ajustes en la app.
- **Borrado** — borra tu cuenta y tu contenido desde Ajustes en la app. Como no tenemos ninguna copia en un servidor, el borrado es completo una vez que se elimina de tu dispositivo y de tu iCloud.
- **Reportar o bloquear** — reporta o bloquea un contacto desde dentro de la app cuando quieras.
- **Oposición / retiro del consentimiento** — deja de usar Faro y borra sus datos en cualquier momento.

Para conocer los derechos según tu región — la UE/EEE (RGPD), el Reino Unido, España (LOPDGDD), California (CCPA/CPRA), otros estados de EE. UU. y el resto del mundo — consulta los [Derechos de Privacidad](https://khassinx.com/es/legal/your-rights/) de KhassinX. Para ejercer cualquiera de ellos en Faro, usa los controles dentro de la app o escribe a [`legal@khassinx.com`](mailto:legal@khassinx.com).

## Etiquetas de Privacidad de Apple

En la ficha del App Store, Faro declara **Datos no recopilados** en todas las categorías. Esto se verifica contra el manifiesto `PrivacyInfo.xcprivacy` y contra el código real: sin SDKs de analytics, sin trackers de terceros, sin frameworks publicitarios, sin un backend que recopile tu contenido.

## Seguridad

- Todo el contenido está **cifrado de extremo a extremo** con CryptoKit de Apple; las claves viven en el Secure Enclave y en el Llavero de iCloud.
- Faro **no** guarda contenido de tu familia en ningún servidor que controlemos.
- La sincronización de iCloud usa el cifrado de Apple, de extremo a extremo cuando tienes activada la Protección de Datos Avanzada.
- Para reportar una vulnerabilidad, mira nuestra política de [Seguridad y divulgación responsable](/es/security/).

## Uso internacional

Como Faro no recopila tus datos ni guarda tu contenido en nuestros servidores, no hay ninguna transferencia transfronteriza de tu contenido por nuestra parte. Tu contenido permanece en tus dispositivos y en tu propio iCloud, donde Apple maneja la residencia y el cifrado.

## Cambios a esta política

Podemos actualizar esta política al agregar funciones que cambien materialmente el manejo de datos, al reflejar cambios en las políticas de Apple, o al corregir errores. Los cambios materiales se reflejarán con una nueva "Fecha de vigencia" arriba y se mostrará un aviso en la app al siguiente arranque.

## Jurisdicción

Esta política se rige por las leyes del **Estado de Florida, Estados Unidos** — la jurisdicción en la que KHASSINX LLC está constituida.

## Contacto

- **Correo**: legal@khassinx.com
- **Postal**: Disponible por escrito a través del correo electrónico

Buscamos responder en siete días hábiles.

---

*Última actualización: 2026-06-12 · Versión 1.0*
