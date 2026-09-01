# CV David Páez 2026
 
## 1. Project Title and Description
 
**CV David Páez 2026** es una versión en HTML/CSS de mi currículum, pensada como proyecto de práctica para el flujo de trabajo de Git. El repositorio contiene una página estática de una sola vista con mi información académica, proyectos y habilidades técnicas.
 
Este proyecto se usó como ejercicio para practicar el flujo completo de Git: ramas, commits, pull requests y documentación, siguiendo la tarea *Homework 1: Git Workflow Practice* del módulo 1.
 
## 2. Technologies Used
 
- **HTML5** — estructura y contenido del CV
- **CSS3** — estilos, tipografía y diseño responsivo
- **Git & GitHub** — control de versiones y flujo de trabajo colaborativo
## 3. Git Workflow Documentation
 
### Estrategia de ramas
 
Se usó una estrategia de **ramas por feature** (*feature branching*): cada parte del proyecto se desarrolló en su propia rama, creada a partir de `main`, y se integró de vuelta mediante un pull request. Esto permitió avanzar en la estructura, el contenido y el estilo del CV de forma aislada, sin tocar directamente `main` en ningún momento.
 
### Ramas creadas
 
| Rama | Contenido |
|---|---|
| `feature/structure` | Creación inicial del archivo HTML y del contenido del `<head>` (metadatos, título, enlace al stylesheet) |
| `feature/content` | Contenido del `<body>`: perfil, educación, proyectos, habilidades técnicas y blandas |
| `feature/styling` | Hoja de estilos `styles.css`: tipografía, colores, layout y diseño responsivo |
 
## 4. Setup Instructions
 
1. Clona el repositorio:
```bash
   git clone https://github.com/Dakewer/git-workflow-practice.git
```
2. Entra a la carpeta del proyecto:
```bash
   cd git-workflow-practice
```
3. Abre `CV_David_Paez_2026.html` directamente en tu navegador (doble clic, o arrastrándolo a una ventana del navegador). No requiere instalación ni servidor, ya que es una página estática.
   - Asegúrate de que `styles.css` esté en la misma carpeta que el archivo HTML, ya que se enlaza mediante una ruta relativa (`<link rel="stylesheet" href="styles.css">`).
