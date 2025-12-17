# Kingdale Technologies Landing

Landing page con branding y animaciones para Kingdale Technologies. Incluye variantes de logo, sección de proyectos y estilos listos para desplegar en Vercel.

## Estructura
- `index.html`: landing principal.
- `assets/logos/`: variantes del logo (`Logo1.png`, `Logo2.png`, `Logo3.png`).
- `assets/images/`: coloca aquí imágenes generales.
- `projects/index.html`: listado de proyectos.
- `projects/project-1/`, `projects/project-2/`: carpetas listas para tus casos de uso.

## Uso local
1) Abre `index.html` en tu navegador (doble clic o desde un servidor local como MAMP).  
2) Edita contenidos según necesites; los logos ya apuntan a `assets/logos/`.

## Deploy con GitHub + Vercel (recomendado)
1) Crea un repositorio en GitHub (vacío, sin README).  
2) En la carpeta del proyecto:
   ```bash
   git init
   git add .
   git commit -m "feat: landing inicial de Kingdale"
   git branch -M main
   git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
   git push -u origin main
   ```
3) Ve a https://vercel.com → Import Project → conecta GitHub → selecciona el repo.  
4) Vercel detectará `index.html` automáticamente; haz deploy.  
5) Cada push a `main` disparará un deploy automático.

## Personalización rápida
- Cambia el logo principal en el header reemplazando `assets/logos/Logo1.png`.  
- Agrega imágenes de proyectos en `assets/images/` y enlázalas desde `projects/`.  
- Añade más proyectos copiando una carpeta en `projects/` y enlazándola desde `projects/index.html`.
