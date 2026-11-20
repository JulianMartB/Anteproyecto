# Modelo 3D · Reproductor físico de audiolibros

Página estática para GitHub Pages que muestra el modelo 3D con rotación, zoom y realidad aumentada en el celular.

## Archivos

```
index.html     ← la página
modelo.glb     ← el modelo 3D (ya incluido, a escala real)
```

## 1. Exportar el modelo como .glb

**Blender:** Archivo › Exportar › glTF 2.0 (.glb/.gltf) → Formato: *glTF Binary (.glb)* → marca *Aplicar modificadores* → guárdalo como `modelo.glb`.

**Autodesk Inventor:** exporta a `.obj` o `.stl`, ábrelo en Blender y expórtalo como `.glb` (paso anterior).

Consejo: aplica materiales y colores en Blender antes de exportar; el visor los respeta. Intenta que pese menos de 10 MB para que cargue rápido.

## 2. Subirlo a GitHub Pages

1. Crea un repositorio nuevo (por ejemplo `reproductor-audiolibros`) o usa una carpeta dentro de tu portafolio.
2. Sube `index.html` y `modelo.glb` a la raíz.
3. Ve a **Settings › Pages**, en *Source* elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En uno o dos minutos queda en `https://TU-USUARIO.github.io/reproductor-audiolibros/`.

## Probarlo antes de subirlo

Si abres `index.html` con doble clic, el navegador no deja cargar `modelo.glb` desde el disco: la página mostrará un recuadro donde puedes **arrastrar el .glb** para verlo. Una vez en GitHub Pages carga solo.

## Cambiar el texto

Todo el texto (título, concepto, controles) está en `index.html`; búscalo y edítalo directamente.
