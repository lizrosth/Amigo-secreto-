# Amigo Secreto

Aplicación web gratuita y adaptable a celulares. Se puede publicar con GitHub Pages.

## Publicar gratis en GitHub Pages

1. Crea un repositorio público llamado `amigo-secreto` en GitHub.
2. Sube `index.html` y `README.md` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que GitHub Pages publique la página. La dirección tendrá el formato `https://TU-USUARIO.github.io/amigo-secreto/`.

## Cómo usar

1. Abre la página publicada.
2. Agrega al menos 3 participantes.
3. Añade las exclusiones necesarias. Cada exclusión se aplica en ambos sentidos.
4. Pulsa **Sortear amigos secretos**.
5. Copia o comparte por WhatsApp el enlace individual de cada participante. Envía cada enlace solamente a su destinatario.

## Límites importantes de esta versión

- Es una aplicación estática: no necesita servidor ni base de datos y no tiene costo de alojamiento en GitHub Pages.
- Los participantes y el sorteo se procesan en el navegador del organizador. No se guardan en una cuenta ni en un servidor.
- Los enlaces individuales contienen únicamente el nombre de la persona y su asignación. El fragmento después de `#` no se envía al servidor web, pero cualquiera que reciba o reenvíe ese enlace podrá ver el resultado.
- El organizador puede conocer las asignaciones al crear los enlaces.
- No hay seguimiento de aperturas, inicio de sesión ni envío automático de correos/SMS.
- Guarda los enlaces después del sorteo. Si cierras o recargas la página del organizador, la lista de participantes y enlaces no se conserva.

Para privacidad fuerte, seguimiento de aperturas o administración desde varios dispositivos se necesita un backend seguro, que GitHub Pages por sí solo no proporciona.
