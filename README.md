# Hola, soy Santiago 👋

**Desarrollador Java · Spring Boot · Android/Kotlin** · Madrid

Estudié Ingeniería Técnica de Telecomunicación hasta el último curso y después de casi 19 años en el sector de la distribución en Lidl, empezando como cajero y llegando a gerente de tienda, he vuelto al sector tecnológico. Como gerente planificaba recursos, analizaba cifras y gestionaba la operativa de la tienda para alcanzar los objetivos, liderando equipos de hasta 35 personas. Ahora aplico esa experiencia al desarrollo de software.

He completado todos los módulos de DAM (2026) y estoy en la fase final de la titulación: la formación en empresa.

🔎 **Busco:** empresa donde realizar la formación en empresa de DAM (prácticas/FCT) y, después, mi primera oportunidad profesional como desarrollador.

## Proyecto destacado

### [StaffFlow](https://github.com/santi-cast/staffflow)

Registro horario y gestión de ausencias para pymes, diseñado en torno a los requisitos de registro horario del RD-ley 8/2019, autoalojado y con fichaje por PIN en una tablet. Nació de ver cómo se llevaba este control a mano en tienda. Proyecto final de DAM (nota 9,4), desarrollado de principio a fin en solitario.

- **Backend:** Java 21, Spring Boot, Spring Security + JWT con roles, JPA/Hibernate y MySQL. 68 endpoints documentados con Swagger.
- **App Android nativa:** Kotlin, MVVM y 30 pantallas.
- **Calidad:** 341 tests unitarios y de controlador, reglas de arquitectura con ArchUnit e integración continua con GitHub Actions.
- **Despliegue:** JAR o Docker, con guía de instalación y documentación técnica.
- **Demo en 5 minutos** con datos de prueba e instrucciones en el README.

## En desarrollo

### [MyCarDisplay](https://github.com/santi-cast/mycardisplay)

Una app Android que convierte una tablet vieja en la pantalla de un coche que no la tiene: muestra Android Auto proyectado desde el móvil (Google Maps, música y asistente) por Wi-Fi local. Nació de tener un coche antiguo, sin pantalla ni navegador. Todo el sonido (música, navegación, llamadas y lectura de mensajes) sigue saliendo por la radio del coche, conectada al móvil por Bluetooth.

Es también mi laboratorio para profundizar en áreas que van más allá del desarrollo Android habitual: protocolos entre dispositivos, TLS, vídeo y APIs multimedia de bajo nivel. Lo desarrollo con un flujo de trabajo asistido por agentes de IA, manteniendo el control sobre el alcance, las decisiones técnicas y la validación del resultado.

- **Stack:** Kotlin, MediaCodec y EGL, con Python para herramientas, tests y una sonda de protocolo.
- **Proceso:** trabajo con agentes de IA sobre **Pi** + [**Gentle Shell**](https://github.com/Gentleman-Programming/gentle-shell) y [**Gentle AI**](https://github.com/Gentleman-Programming/gentle-ai), aplicando **SDD** (especificación antes del código), **ODD** (trabajo en unidades pequeñas con sus tests) y **RDD** (revisión independiente de cada cambio), además de diagnóstico con dispositivos reales: el agente opera `adb` con permisos que yo autorizo y compara nuestras sesiones con un sistema de referencia.
- **Estado:** el código aún no es público. Núcleo de sesión y decodificador implementados y testeados; la sonda de protocolo ya consigue que el móvil acepte la sesión y abra todos los canales; el siguiente paso es el primer vídeo en la tablet.

## Otros proyectos

### [DeskMusicPlayer](https://github.com/santi-cast/deskmusicplayer)

Un móvil antiguo (Android 8.1, sin actualizaciones de seguridad desde 2019 y con la batería gastada) convertido en un reproductor de música fijo en el escritorio, bloqueado a las apps de música. Nació de reaprovechar un aparato que iba al cajón en lugar de tirarlo. 

- **App Android nativa en Kotlin** que hace de pantalla de inicio y, como *device owner*, bloquea el móvil en modo kiosco a las apps elegidas.
- **Salvapantallas con lo que está sonando**, gestos de brillo y volumen, logos de las emisoras de FM e instalación de apps sin salir del bloqueo.
- **Pensado para montarse sin ordenador** y sin cuenta de Google, con una configuración inicial guiada desde el propio móvil.
- **Proceso:** desarrollado con agentes de IA (Pi + Gentle Shell y Gentle AI), con test-first (54 tests), commits pequeños y cada función probada en el dispositivo real.
- **Estado:** versión 1.1.0 publicada, con el APK firmado en [Releases](https://github.com/santi-cast/deskmusicplayer/releases) y un código QR para activar el modo kiosco sin ordenador.
  
## Tecnologías

![Java](https://img.shields.io/badge/Java-21-orange?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5-6DB33F?logo=springboot&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-2.1-7F52FF?logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-nativo-3DDC84?logo=android&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

## Cómo trabajo

- Me gusta entender el problema antes de empezar a programar y convertirlo en decisiones técnicas concretas. StaffFlow nació de una necesidad que conocía de primera mano y lo llevé desde la idea hasta un sistema completo con backend, aplicación Android, seguridad, documentación y despliegue.
- No considero terminado un desarrollo solo porque funcione: en StaffFlow incorporé 341 tests, reglas de arquitectura con ArchUnit e integración continua con GitHub Actions.
- Documento las decisiones importantes y también las limitaciones conocidas del proyecto, para que quede claro no solo **qué** hace el código, sino también **por qué** se ha diseñado de esa manera y qué queda por mejorar.
- En MyCarDisplay estoy llevando esa forma de trabajar a problemas técnicos nuevos y al desarrollo asistido por agentes: especificación antes del código, unidades pequeñas con sus tests y revisión independiente de cada cambio, manteniendo yo el control sobre el alcance y las decisiones técnicas.

## Contacto

📫 santicast@gmail.com
