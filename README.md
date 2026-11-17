# MARec

Grabadora de audio para el móvil y el ordenador: grabación manual, automática por sonido o continua y programada, categorías, notas, adjuntos y grabaciones bloqueadas y cifradas. En el PC, además, separa quién habla y transcribe lo que dice, sin internet.

**Aplicación gratuita para Windows y Android desarrollada por [Masoft.es](https://masoft.es)**

- **Windows 1.2.0:** [instalador](https://github.com/MaSoft/MARec/releases/download/escritorio-v1.2.0/MARec_Escritorio_Setup_v1.2.0.exe) o [ejecutable único](https://github.com/MaSoft/MARec/releases/download/escritorio-v1.2.0/MARec_v1.2.0.exe)
- **Android 1.5.0:** [APK](https://github.com/MaSoft/MARec/releases/download/android-v1.5.0/MARec-1.5.0.apk)
- **Reloj (Wear OS), MARecClock 1.1.0:** [APK del reloj](https://github.com/MaSoft/MARec/releases/download/reloj-v1.1.0/MARecClock-1.1.0.apk) (opcional, necesita la app del móvil)

Más información y los manuales también en [masoft.es](https://masoft.es/descargas.html#marec).

![MARec en el ordenador y en el móvil](capturas/01-portada-portada.webp)

**Funcionan juntas.** El PC hace de servidor y el móvil se sincroniza con él por la Wi-Fi, en los dos sentidos: emparejados con un código QR y cifrado, sin cuentas ni nube. Cada una funciona también sola.

## Windows 1.2.0

**Windows 10 / 11 · 64 bits** · [Página de la versión](https://github.com/MaSoft/MARec/releases/tag/escritorio-v1.2.0)

- **Instalador:** [`MARec_Escritorio_Setup_v1.2.0.exe`](https://github.com/MaSoft/MARec/releases/download/escritorio-v1.2.0/MARec_Escritorio_Setup_v1.2.0.exe) · 167,9 MB · SHA-256 `fe31a6a8fd11b8ad4132928e572de82500e1e3d58f571a10a364133a7924f336`
- **Ejecutable único (sin instalar):** [`MARec_v1.2.0.exe`](https://github.com/MaSoft/MARec/releases/download/escritorio-v1.2.0/MARec_v1.2.0.exe) · 256,7 MB · SHA-256 `d0f3439d5b2ce790754d47b6dc76df0226bddcd4db50bd99a20f322a4f54c968`

### Qué hace
- Biblioteca de grabaciones con árbol de categorías y subcategorías, favoritas, bloqueadas y «Sin categoría».
- Organizar a dos columnas: una categoría a cada lado, se mueven grabaciones con flechas o arrastrando.
- Reproductor con forma de onda y marcas; las partes de una grabación se oyen seguidas. Marcas, nota y adjuntos.
- Voces y texto: separa quién habla, pone el nombre de cada persona y transcribe lo que dice. En el PC, sin internet.
- Buscar lo que se dijo: el buscador encuentra las palabras de las transcripciones y la página Voces enseña lo que dice cada persona.
- Transcripción a Word, PDF, texto y página web; las palabras dudosas salen en gris para repasarlas.
- Editar el audio: quitar trozos, recortar, dividir y quitar silencios; guarda grabaciones nuevas y la original no se toca.
- Importar audios sueltos o carpetas y exportar a ZIP o carpeta, por categorías.
- Grabar con el micrófono del PC, con pausa, marcas y onda en vivo.
- Todo cifrado en tu PC; sincronización con el móvil por la Wi-Fi emparejando con un código QR.

### Requisitos

| | |
|---|---|
| Sistema | Windows 10 u 11 de 64 bits |
| Micrófono | Solo para grabar en el PC. |
| Red | Solo para sincronizar: el PC y el móvil en la misma red, puerto 47890 permitido en redes privadas. |
| Voces y texto | Procesador de 4 núcleos o más, 8 GB de memoria y 3,1 GB de disco. Internet solo una vez, para descargar los modelos. |
| Instalación | Instalador para tu usuario, sin permisos de administrador, o ejecutable único que se copia y se abre; Python va dentro. |

### Capturas

| | |
|---|---|
| ![Grabaciones](capturas/02-pc-pc_grabaciones.webp)<br>**Grabaciones.** Árbol de categorías, filtros y la tabla con todas las grabaciones. | ![Ficha](capturas/03-pc-pc_ficha.webp)<br>**Ficha.** Reproductor con onda y marcas, categoría, voces y texto. |
| ![Transcripción](capturas/04-pc-pc_transcripcion.webp)<br>**Transcripción.** Cada frase con su momento y la persona que habla; clic y el audio salta ahí. | ![Voces](capturas/05-pc-pc_voces.webp)<br>**Voces.** Las personas con nombre y todo lo que dice cada una. |
| ![Organizar](capturas/06-pc-pc_organizar.webp)<br>**Organizar.** Dos columnas para mover grabaciones y gestionar categorías. | ![Editar el audio](capturas/07-pc-pc_editar.webp)<br>**Editar el audio.** Quitar, recortar, dividir y quitar silencios sin tocar la original. |

## Android 1.5.0

**Android 10 o superior** · [Página de la versión](https://github.com/MaSoft/MARec/releases/tag/android-v1.5.0)

- **APK:** [`MARec-1.5.0.apk`](https://github.com/MaSoft/MARec/releases/download/android-v1.5.0/MARec-1.5.0.apk) · 61,2 MB · SHA-256 `fedfdf6f2e6f52cc20cc7b5c53907ede397799cdeb8accc3930fa13e38cd5da9`

### Qué hace
- Manual o Automático: graba al pulsar o solo cuando hay sonido por encima del umbral, sin perder los segundos de antes.
- Programaciones por franja horaria, días de la semana o fecha concreta, también de día completo o pasando la medianoche.
- En Automático, si el sonido vuelve tras una pausa sigue en la misma grabación, sin guardar el silencio.
- Categorías con color y subcategorías, favoritas, agrupaciones y búsqueda por nombre, nota o categoría.
- Marcas, nota y adjuntos (imágenes o documentos) en cada grabación.
- Reproductor con forma de onda, saltos de 10 s, velocidad y saltar silencios; editor para quitar, recortar, dividir y quitar silencios.
- Bloquear cifra la grabación y sus adjuntos; para borrarla hay que escribir BORRAR.
- Widget y botón en los ajustes rápidos para grabar sin abrir la app; Lugares que dan nombre y categoría a lo grabado allí.
- Limpieza que pregunta: propone las antiguas o las que pasan de un tamaño y tú eliges. Nunca borra sola.
- Sincronización con MARec del PC por la Wi-Fi, y «Quitar del móvil» lo que el PC ya tiene entero para liberar espacio.

### Requisitos

| | |
|---|---|
| Sistema | Android 10 o superior |
| Permisos | Micrófono (imprescindible); avisos, alarmas exactas y sin ahorro de batería, recomendados para programar; ubicación solo para Lugares. |
| Internet | No hace falta: las grabaciones se quedan en el móvil y la sincronización va por la Wi-Fi de casa u oficina. |
| Instalación | Se descarga el APK en el móvil y se abre; Android pide permiso para instalar aplicaciones de esa fuente. |
| Actualizar | La versión nueva se instala encima de la anterior sin perder las grabaciones. |

### Capturas

| | |
|---|---|
| ![Grabar](capturas/08-movil-grabar.webp)<br>**Grabar.** Manual o Automático con su medidor de nivel, y grabando con marcas. | ![Grabaciones](capturas/09-movil-grabaciones.webp)<br>**Grabaciones.** Por días o por categorías, con favoritas, bloqueadas y adjuntos a la vista. |
| ![Ficha y editor](capturas/10-movil-ficha.webp)<br>**Ficha y editor.** Reproductor con onda y marcas, nota y adjuntos; y el editor de audio. | ![Programar y Lugares](capturas/11-movil-programar.webp)<br>**Programar y Lugares.** Franjas por horas y días, y los lugares que dan nombre a lo grabado allí. |

## Reloj (Wear OS): MARecClock 1.1.0

**Wear OS 3 o superior · con MARec en el móvil** · [Página de la versión](https://github.com/MaSoft/MARec/releases/tag/reloj-v1.1.0)

- **APK:** [`MARecClock-1.1.0.apk`](https://github.com/MaSoft/MARec/releases/download/reloj-v1.1.0/MARecClock-1.1.0.apk) · 2,6 MB · SHA-256 `5cf672ef68f94136ce3382dd5b73c9ccc37bebeb6336b53921962e75d39775a3`

### Qué hace
- Detectando sonido: graba solo cuando hay sonido por encima del umbral, con los 3 segundos de antes; si vuelve antes de 2 minutos, sigue en la misma grabación.
- Continua: una sola grabación desde que pulsas hasta que paras.
- Un toque en cualquier parte de la pantalla pausa o sigue en la misma grabación y dos toques la paran, con una vibración como respuesta. Sin sonidos.
- Al parar, cada grabación se guarda o se elimina en el propio reloj; también «Guardar todas» y «Eliminar todas», con confirmación.
- Lo guardado pasa solo al móvil, a «Grabaciones Reloj», aunque el reloj entre en reposo; se borra del reloj solo cuando el móvil confirma que lo tiene.
- Umbral y silencio para cortar ajustables en el propio reloj.

### Requisitos

| | |
|---|---|
| Reloj | Wear OS 3 o superior, de cualquier marca. |
| Móvil | MARec 1.5.0 o posterior en el móvil emparejado con el reloj: sin él no funciona. |
| Permisos | Micrófono (imprescindible) y avisos; se piden la primera vez que se graba. |
| Internet | No hace falta: el envío va del reloj al móvil por su conexión directa. |
| Instalación | Desde un ordenador, con la depuración inalámbrica del reloj: los pasos, en la página Relojes de masoft.es y en el manual. |
| Actualizar | La versión nueva se instala encima sin perder las grabaciones del reloj. |

### Capturas

| | |
|---|---|
| ![Grabar](capturas/12-reloj-grabar.webp)<br>**Grabar.** Los dos modos y la grabación en marcha, con el tiempo, el estado y el nivel de sonido. | ![Pausa y ajustes](capturas/13-reloj-pausa_ajustes.webp)<br>**Pausa y ajustes.** En pausa con un toque, y el umbral y el silencio de Detectando sonido. |
| ![Guardar o eliminar](capturas/14-reloj-guardar.webp)<br>**Guardar o eliminar.** Guardar todas al móvil o eliminarlas, y la ficha de una grabación. |  |

Manual con la instalación paso a paso: [manual_MARecClock.html](https://github.com/MaSoft/MARec/releases/download/reloj-v1.1.0/manual_MARecClock.html) (descárgalo y ábrelo en el navegador). También en [masoft.es](https://masoft.es/relojes.html#marecclock).

## Instalación y comprobación

- **Windows:** el instalador y el ejecutable no están firmados digitalmente: Windows puede mostrar «Windows protegió su PC». Pulsa «Más información» y «Ejecutar de todas formas».
- **Android:** las aplicaciones no están en Google Play. Se descarga el APK en el móvil y se abre; Android pide permiso para instalar aplicaciones de esa fuente y Google Play Protect puede avisar de que no conoce la aplicación.
- **Reloj (Wear OS):** el APK del reloj no se instala tocándolo como en el móvil: se pasa desde el ordenador con la depuración inalámbrica del reloj (`adb pair`, `adb connect` y `adb install`). El reloj tiene que estar emparejado con el móvil que tiene MARec.

Para comprobar una descarga, en PowerShell `Get-FileHash .\<archivo>` debe dar la huella SHA-256 de arriba.

## Aviso legal

MARec es gratuito y se entrega tal cual, sin garantía de ningún tipo. Al descargarlo y usarlo aceptas el aviso legal y las limitaciones de su manual.

> ⚠ Grabar una conversación en la que participas es legal. Grabar a otras personas sin estar tú en la conversación ni tener su permiso puede ser delito (art. 197 del Código Penal). El modo Automático y la grabación continua programada pueden captar a cualquiera que hable cerca del móvil, y en el reloj Detectando sonido y Continua también: úsalos solo donde tengas derecho a grabar. Difundir una grabación también puede vulnerar derechos de las personas grabadas.
> ⚠ Voces y texto (PC): la huella de voz de una persona es un dato biométrico (RGPD, art. 9). Ponerle nombre a la voz de otra persona y guardarla requiere su consentimiento. La transcripción y los nombres son automáticos y pueden tener errores: no los uses como prueba sin escuchar el audio.

**Limitaciones y exclusión de responsabilidad**
- La responsabilidad del uso de las grabaciones es de quien las hace.
- Las grabaciones programadas dependen de que Android y el fabricante mantengan la app en marcha: no se garantiza que ninguna franja se grabe completa.
- En el móvil las grabaciones se guardan solo dentro de la app: si se desinstala o se borran sus datos, se pierden. Exporta antes lo que quieras conservar.
- En el PC los datos se guardan cifrados en este equipo: si se pierde la carpeta DATA o el usuario de Windows, no se pueden recuperar desde ahí (sí desde un móvil emparejado).
- El cifrado protege frente a quien copie los archivos, no frente a quien use el móvil desbloqueado o tu sesión de Windows abierta.
- El reloj (MARecClock) no funciona sin MARec en el móvil: las grabaciones se quedan en el reloj hasta que el móvil confirma que las tiene.
- MARec se proporciona tal cual, sin garantía de ningún tipo.

Este repositorio solo contiene las aplicaciones compiladas y su documentación. © Masoft.es. Todos los derechos reservados.
