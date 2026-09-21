# 10 meses — juego para Kath

Página web con el juego de 4 niveles (corazones, recuerdos, plataformas y memes) que termina con la carta.

## Estructura

```
index.html          ← todo el juego (HTML + CSS + JS)
images/
  foca-audifonos.jpg
  tigre.jpg
  morsa-bigote.jpg
  gato-blanco-negro.jpg
  hombre-audifonos.jpg
  gato-borroso.jpg
```

## Cómo subirlo a GitHub Pages

1. Entra a [github.com](https://github.com) y crea un repositorio nuevo (por ejemplo `10-meses-kath`). Puede ser público.
2. Sube estos archivos y esta carpeta tal cual están (botón **"Add file" → "Upload files"**, o con git si prefieres).
3. Ve a **Settings → Pages** dentro del repositorio.
4. En "Build and deployment", selecciona **Source: Deploy from a branch**, rama **main**, carpeta **/ (root)**. Guarda.
5. Espera 1–2 minutos. Tu página quedará publicada en:
   `https://tu-usuario.github.io/10-meses-kath/`

Ese link es el que le puedes mandar a Kath. Al abrirlo en Chrome desde su celular, puede usar el menú (⋮) → **"Añadir a pantalla de inicio"** para que le quede como un ícono de app.

## Notas

- No necesita servidor ni build: es HTML/CSS/JS puro, funciona con solo subir los archivos.
- Si quieres cambiar una imagen, reemplaza el archivo en `images/` manteniendo el mismo nombre, o cambia el nombre en el arreglo `memes` dentro de `index.html`.
- El repositorio puede quedar privado si prefieres — GitHub Pages funciona igual, aunque con cuenta gratuita la página publicada sigue siendo accesible por el link para quien lo tenga.
