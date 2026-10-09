# Política de privacidad de IMachX

Responsable: Imanol Machado. Se respeta la decisión de no utilizar un correo de contacto del desarrollador.

`index.html` contiene el borrador y su diseño para GitHub Pages. El correo electrónico mencionado entre los datos de cuenta es el de los usuarios, necesario para el acceso actual de IMachX; no es un correo de soporte.

## Pendientes antes de publicar

1. Crear un mecanismo real de consultas de privacidad y solicitudes de eliminación. Se ha preparado el texto para un formulario privado; todavía no existe ni se ha desplegado. Debe permitir atender al solicitante y verificar su identidad sin publicar sus datos. El responsable necesita una forma de revisar las solicitudes y responderlas. GitHub Pages aloja archivos estáticos y no procesa por sí mismo formularios; el formulario necesitará un servicio que reciba las solicitudes.
2. Sustituir `[URL DEL FORMULARIO DE PRIVACIDAD]` y convertir su texto en un enlace HTML accesible. Para Google Play, el recurso de eliminación debe poder usarse sin reinstalar la app. No usar una incidencia pública de GitHub para pedir contraseñas, correos o datos de cuentas.
3. Confirmar y completar los plazos de registros, sesiones, copias de seguridad y solicitudes. No se han inventado configuraciones del proveedor ni compromisos de atención que el responsable no haya aceptado.
4. Definir el plazo real de atención de solicitudes de eliminación. El procedimiento debe eliminar la cuenta de Appwrite, sus sesiones y su registro asociado de nombres; desactivar la cuenta o desinstalar la app no basta.
5. Retirar el aviso de borrador cuando todos los campos estén completos. Buscar `[` para localizar los campos pendientes.

El documento describe el tratamiento de solicitudes como política propuesta; no implementa el formulario ni el proceso de eliminación. Al implementarlos, revisar los datos nuevos que recojan, su proveedor y sus plazos antes de publicar. La app Android actual todavía no incluye un enlace a la política ni un mecanismo de solicitud de eliminación.

## Publicar en GitHub Pages

1. Crea un repositorio para esta página y sube **solo `index.html`** a la raíz. No subas el proyecto entero, carpetas `private`, archivos `.env` ni claves.
2. En el repositorio abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, la rama **main** y **/(root)**; guarda.
4. GitHub mostrará la URL publicada, habitualmente `https://TU_USUARIO.github.io/NOMBRE_DEL_REPOSITORIO/`. Esta dirección debe estar accesible sin iniciar sesión.
5. Añade la URL de la política a Play Console y un enlace visible en la app. Para el campo de eliminación de cuentas, usa la dirección pública del formulario o página que ofrezca ese procedimiento. Esta política incluye un ancla `#eliminar-cuenta`, pero el texto solo no sustituye un canal funcional de solicitudes.

El repositorio usado para publicar la política no necesita llamarse IMachX. La configuración y ubicación de Pages dependen de tu plan y tipo de repositorio.

Fuentes consultadas:

- [Datos de usuario y requisitos de la política de privacidad de Google Play](https://support.google.com/googleplay/android-developer/answer/10144311?hl=es).
- [Solicitudes de eliminación de cuentas](https://support.google.com/googleplay/android-developer/answer/13327111?hl=es).
- [Seguridad y persistencia de sesiones de Appwrite](https://appwrite.io/docs/products/auth/security).
- [Configurar la publicación de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
