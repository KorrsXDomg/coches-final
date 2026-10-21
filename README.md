# APEX MOTORS — Showroom estático

Versión HTML estática del showroom de lujo **APEX MOTORS**, lista para publicar en **GitHub Pages**.

## Contenido

- Catálogo de 12 vehículos de alta gama (Porsche, Ferrari, Lamborghini, Bugatti, Tesla, etc.)
- Selector de colores por modelo (imágenes incluidas)
- Favoritos (guardados en `localStorage`)
- Comparador de hasta 2 coches
- Simulador de financiación
- Formulario de contacto / cotización
- Diseño oscuro de lujo (tipografías Oswald + Outfit)

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (público o privado).
2. Sube **todo el contenido de esta carpeta** a la raíz del repo (o a una carpeta `/docs`).
3. En el repositorio: **Settings → Pages → Source**:
   - Branch: `main` (o `master`)
   - Folder: `/ (root)` o `/docs` según donde hayas subido los archivos.
4. Guarda. En 1–2 minutos tendrás la URL:  
   `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

## Estructura

```
apex-motors-static/
├── index.html          ← página principal (todo el sitio)
├── cars-data.json      ← datos del catálogo
├── favicon.svg
├── og.jpg              ← (opcional)
├── cars/               ← imágenes de los vehículos
│   ├── porsche-rojo.jpg
│   ├── ferrari-*.jpg
│   └── ...
└── README.md
```

## Notas

- Es una versión estática fiel al diseño y a la información del proyecto original.
- No requiere build ni servidor: abre `index.html` localmente o súbelo a cualquier hosting estático.
- Las solicitudes de contacto y favoritos funcionan en el navegador (demo).
