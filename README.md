# 🌎 Tratados de Libre Comercio de México

Página interactiva con un globo terráqueo 3D (canvas) que muestra los Tratados de Libre Comercio de México: países participantes, fechas de firma, entrada en vigor, temas principales, motivo de la firma, lugar e impacto económico.

**Realizado por:** Yáñez Vladimir

## Características
- Globo 3D arrastrable con animación de entrada, rutas desde México y paquetes de datos.
- Pines con banderas reales (SVG incrustados). Al tocar un pin se abre una tarjeta flotante.
- Botón **Ver todos los tratados** y línea del tiempo (1992–2020) para navegar por año.
- 100 % estático: un solo archivo `index.html`, sin dependencias ni servidor.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `tlc-mexico`).
2. Sube los archivos del zip a la raíz del repositorio (`index.html`, `404.html`, `README.md`, `.nojekyll`).
3. En el repositorio ve a **Settings → Pages**.
4. En **Build and deployment** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y pulsa **Save**.
5. En uno o dos minutos la página estará en `https://TU-USUARIO.github.io/tlc-mexico/`.

### Desde la terminal
```bash
git init
git add .
git commit -m "Tratados de Libre Comercio de México"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/tlc-mexico.git
git push -u origin main
```

## Nota sobre los datos
Las fechas y datos son material de referencia. Verifícalos en la Secretaría de Economía (https://www.gob.mx/se), sobre todo el estado actual del T-MEC y la modernización del acuerdo con la UE.
