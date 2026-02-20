# Política de Privacidad

**Dragon Hoard - Rastreador de Colección de Juegos**

Última actualización: 20 de febrero de 2026

---

## 1. Introducción

Dragon Hoard ("nosotros", "nuestro" o "nos") opera la aplicación móvil Dragon Hoard (la "App"). Esta Política de Privacidad explica cómo recopilamos, usamos y protegemos su información personal cuando utiliza nuestra App.

Al usar Dragon Hoard, usted acepta la recopilación y uso de información según lo descrito en esta política.

---

## 2. Información que Recopilamos

### 2.1 Información de la Cuenta
- **Dirección de correo electrónico**: Requerida para la creación de cuenta e inicio de sesión (al usar inicio de sesión por correo)
- **Apple ID**: Si inicia sesión con Apple, recibimos su nombre y correo electrónico (o una dirección relay si elige ocultarlo)
- **Cuentas de invitado**: Puede usar la App sin proporcionar información personal. Las cuentas de invitado son anónimas y están vinculadas solo a su dispositivo.

### 2.2 Datos de la Colección de Juegos
- Títulos de juegos, plataformas y estado (pendiente, jugando, completado)
- Precios de compra y valores de mercado estimados
- Condición del juego, región y cantidad
- Notas personales y calificaciones
- Elementos de la lista de deseos

### 2.3 Cámara y Fotos
- Al usar la función de Escáner de Estantería, la App accede a su cámara para fotografiar estanterías de juegos
- Las fotos se envían a Google Gemini AI para identificación de juegos y **no se almacenan** en nuestros servidores
- Las fotos se procesan solo en memoria y se descartan inmediatamente después de la identificación

### 2.4 Datos de Uso
- Estadísticas de uso de funciones de la App (solo con su consentimiento)
- Datos de seguimiento de ahorros
- Progreso de logros e insignias
- Racha diaria y progresión de XP

### 2.5 Información Técnica
- Tipo de dispositivo y sistema operativo (para compatibilidad de la App)
- Versión de la App
- Configuración regional del dispositivo (para moneda e idioma)

**Nota:** Con su consentimiento explícito, podemos recopilar informes de fallos anonimizados y estadísticas de uso para mejorar la App (ver Sección 4.5). Puede activar o desactivar esto en cualquier momento en la configuración de la App.

---

## 3. Cómo Usamos Su Información

Usamos su información para:
- Proporcionar y mantener la funcionalidad de la App
- Sincronizar su colección de juegos entre dispositivos
- Calcular el valor de mercado estimado de su colección basado en datos de ventas públicas
- Rastrear sus ahorros y objetivos de juego
- Enviar notificaciones importantes del servicio
- Mejorar la App basándonos en patrones de uso (con consentimiento)

**No** vendemos su información personal a terceros.

---

## 4. Servicios de Terceros

Dragon Hoard utiliza los siguientes servicios de terceros:

### 4.1 Supabase (Base de Datos y Autenticación)
- Almacena los datos de su cuenta y colección en servidores seguros
- Gestiona la autenticación (correo/contraseña e inicio de sesión anónimo)
- Los datos están protegidos por Row Level Security — solo usted puede acceder a sus datos
- Política de Privacidad: https://supabase.com/privacy

### 4.2 RevenueCat (Gestión de Suscripciones)
- Gestiona las suscripciones premium y compras dentro de la App
- Recibe su ID de usuario anónimo y estado de suscripción
- No recibe su correo electrónico, nombre ni datos de colección de juegos
- Política de Privacidad: https://www.revenuecat.com/privacy

### 4.3 Google Gemini AI (Escáner de Estantería)
- Procesa fotos para identificar juegos en sus estanterías
- Las imágenes se envían a través de nuestro servidor seguro (Supabase Edge Function), no directamente desde su dispositivo
- Las imágenes se procesan en tiempo real y **no se almacenan** por nosotros ni por Google más allá de la solicitud
- Política de Privacidad: https://policies.google.com/privacy

### 4.4 IGDB (Base de Datos de Juegos)
- Proporciona información de juegos, imágenes de portada y metadatos
- Solo se envían consultas de búsqueda de juegos — sin datos personales
- Política de Privacidad: https://www.igdb.com/privacy_policy

### 4.5 Firebase Analytics y Crashlytics (Google)
- Recopila estadísticas de uso anonimizadas e informes de fallos (**solo con su consentimiento**)
- No se comparten datos personales — solo métricas agregadas
- Puede desactivarlo en cualquier momento en la configuración de la App
- Política de Privacidad: https://firebase.google.com/support/privacy

### 4.6 Jina.ai y eBay (Estimación de Precios)
- Se utiliza para estimar valores de mercado de juegos a partir de listados de ventas completadas de eBay disponibles públicamente
- Jina.ai lee páginas de resultados de búsqueda públicas de eBay en nuestro nombre
- Solo se envían títulos de juegos y nombres de plataformas — **sin datos personales**
- Las estimaciones de precios son aproximadas y se basan en ventas completadas recientes
- Política de Privacidad (Jina): https://jina.ai/legal/privacy-policy

---

## 5. Almacenamiento y Seguridad de Datos

- Sus datos se almacenan en servidores seguros proporcionados por Supabase
- Toda la transmisión de datos está cifrada usando HTTPS/TLS
- Las contraseñas se hashean y nunca se almacenan en texto plano
- Los datos locales sensibles (estado de suscripción, progreso) se almacenan en el Keychain cifrado de su dispositivo
- Las preferencias no sensibles se almacenan localmente en su dispositivo
- Implementamos medidas de seguridad estándar de la industria

---

## 6. Sus Derechos

Usted tiene derecho a:
- **Acceso**: Solicitar una copia de sus datos personales
- **Corrección**: Actualizar o corregir su información
- **Eliminación**: Eliminar su cuenta y todos los datos asociados (disponible en la configuración de la App)
- **Exportación**: Exportar los datos de su colección de juegos (función de exportación PDF)

La eliminación de cuenta elimina permanentemente todos sus datos de nuestros servidores y borra todos los datos almacenados localmente de su dispositivo.

Para ejercer estos derechos, use la configuración de la App o contáctenos por correo electrónico.

---

## 7. Retención de Datos

- Cuentas activas: Los datos se conservan mientras la cuenta esté activa
- Cuentas eliminadas: Todos los datos se eliminan permanentemente de inmediato
- Informes de fallos anónimos: Se conservan hasta 90 días

---

## 8. Transferencias Internacionales de Datos

Sus datos pueden procesarse en países fuera de su país de residencia. Los servidores de Supabase pueden estar ubicados en la UE o EE.UU. Todas las transferencias están protegidas por cifrado HTTPS y cumplen con las regulaciones de protección de datos aplicables.

---

## 9. Privacidad de los Niños

Dragon Hoard no está destinado a niños menores de 13 años. No recopilamos conscientemente información personal de niños menores de 13 años.

---

## 10. Cambios a Esta Política

Podemos actualizar esta Política de Privacidad de vez en cuando. Le notificaremos sobre cambios significativos a través de la App o por correo electrónico.

---

## 11. Contáctenos

Si tiene preguntas sobre esta Política de Privacidad o sus datos personales:

**Correo electrónico**: hoardgamecollection@gmail.com

---

*Esta Política de Privacidad es efectiva a partir del 20 de febrero de 2026.*
