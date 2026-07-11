<p align="center">
  <a href="README.md">English</a> · <strong>Español (España)</strong>
</p>

<p align="center">
  <img src="assets/zencode-icon.png" width="112" height="112" alt="Icono de la aplicación Zencode">
</p>

<h1 align="center">Zencode</h1>

<p align="center"><strong>Convierte conversaciones en software funcional.</strong></p>

Zencode es un espacio de trabajo de escritorio para desarrollar software con agentes de programación de IA. Reúne la conversación, el contexto del proyecto, la actividad del terminal, los cambios en archivos, el flujo de trabajo de Git, los permisos y la verificación en un solo lugar, para que puedas pasar de una idea a un cambio revisado sin perder de vista lo que hace el agente.

## Beta pública

Zencode se encuentra actualmente en fase beta pública. Las versiones preliminares pueden contener errores, cambiar entre versiones o requerir migraciones a medida que evoluciona el producto. Haz copias de seguridad del trabajo importante y revisa los cambios generados por los agentes antes de confirmarlos, enviarlos o publicarlos.

La versión compatible más reciente está disponible en la página de [versiones](https://github.com/zencode-chat/zencode/releases). Durante la beta, las versiones aparecen marcadas como **Pre-release**.

## Qué puedes hacer con Zencode

- Abrir un proyecto y trabajar con agentes en conversaciones que conocen el contexto del proyecto.
- Adjuntar archivos relevantes y añadir contexto del repositorio a una solicitud.
- Utilizar las integraciones gestionadas de OpenAI Codex y Claude Agent.
- Conectar Anthropic, OpenAI y Z.ai con tus propias credenciales de API.
- Seguir los comandos del terminal, la actividad de las herramientas, los permisos y los eventos de ejecución.
- Revisar diferencias y gestionar el área de preparación, las confirmaciones, los remotos, los envíos y las solicitudes de incorporación de cambios.
- Ejecutar tareas recurrentes mediante automatizaciones vinculadas a un proyecto.
- Conectar servidores MCP seleccionados o personalizados para disponer de herramientas adicionales.
- Dictar solicitudes mediante transcripción de voz en el dispositivo.

Los proveedores y modelos tienen capacidades diferentes. La compatibilidad con archivos adjuntos, las herramientas, los límites de contexto, los controles de razonamiento, los precios y el comportamiento de red dependen del proveedor y del modelo que selecciones.

## Tu espacio de trabajo y los servicios conectados

Zencode conserva en tu ordenador el estado del espacio de trabajo, el acceso a proyectos, la base de datos de conversaciones, las operaciones de Git, las sesiones del terminal, los permisos y la transcripción de voz. Las grabaciones de voz son archivos temporales de procesamiento y no se guardan como archivos adjuntos de las conversaciones.

Zencode no ejecuta localmente los modelos de IA seleccionados. Las solicitudes y el contexto que envíes se transmiten al proveedor remoto que elijas. Los agentes gestionados, los proveedores de modelos, los servidores MCP, los servicios de alojamiento de Git y otras integraciones pueden acceder a la red cuando los habilitas o utilizas, y siguen sujetos a sus propios términos y prácticas de privacidad.

## Descargas

Actualmente se generan versiones oficiales para:

- macOS en equipos con Apple silicon;
- macOS en equipos Intel;
- Windows x64; y
- Linux x64 en formato AppImage.

Descarga Zencode únicamente desde la [página oficial de versiones](https://github.com/zencode-chat/zencode/releases). Este repositorio público es el canal de distribución y actualización de Zencode; no contiene el código fuente privado de la aplicación.

### Verificar una descarga

Cada versión incluye un manifiesto de integridad `SHA256SUMS.txt`. Antes de instalarla, compara la suma de comprobación de la descarga con la entrada correspondiente.

- Las versiones para macOS están firmadas con Developer ID, protegidas mediante el entorno de ejecución reforzado y notarizadas por Apple. No omitas Gatekeeper si macOS no puede validar la aplicación.
- Las versiones para Windows están firmadas digitalmente. Comprueba las **Firmas digitales** en las propiedades del instalador antes de ejecutarlo.
- En Linux, verifica la suma de comprobación de la AppImage antes de convertirla en ejecutable.

Si una firma, suma de comprobación, nombre de archivo o página de versión parece inesperado, no instales el archivo. Informa del problema de forma privada mediante el [formulario de avisos de seguridad de GitHub](https://github.com/zencode-chat/zencode/security/advisories/new).

## Actualizaciones

Zencode utiliza paquetes de versión firmados y metadatos de actualización publicados en este repositorio. Las instalaciones beta reciben actualizaciones beta compatibles a medida que están disponibles. Los instaladores, los metadatos de actualización, los mapas de bloques, las sumas de comprobación, las etiquetas y el historial de versiones permanecen visibles de forma independiente en la página de cada versión.

## Seguridad

No divulgues en una incidencia pública posibles vulnerabilidades, descargas comprometidas, credenciales expuestas o problemas de firma. Sigue las instrucciones de comunicación privada de [SECURITY.md](SECURITY.md).

## Licencia

Zencode es software propietario y se proporciona bajo licencia, no se vende. La descarga de una versión solo concede los derechos de usuario final establecidos en el [Acuerdo de licencia de software propietario de Zencode](LICENSE). No concede permiso para redistribuir, modificar, volver a empaquetar, aplicar ingeniería inversa ni crear productos derivados de Zencode.

Los componentes y servicios de terceros continúan sujetos a sus respectivas licencias y condiciones.

Copyright © 2026 Zencode. Todos los derechos reservados.
