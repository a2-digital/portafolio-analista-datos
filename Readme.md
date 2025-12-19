# 📊 Portafolio - Andrés Aranguren

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Andrés_Aranguren-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres-aranguren-b758a3211)
[![GitHub](https://img.shields.io/badge/GitHub-a2--digital-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/a2-digital)
[![Email](https://img.shields.io/badge/Email-andresdal090@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andresdal090@gmail.com)

> **Portafolio profesional de Analista de Datos Junior** especializado en SQL, Python, Power BI y Excel.

[🌐 Ver Portafolio en Vivo](#) <!-- Agregar el link de GitHub Pages -->

---

## 🎯 Sobre el Proyecto

Este portafolio web presenta mi experiencia, habilidades y proyectos como Analista de Datos. Desarrollado con tecnologías modernas y diseño responsive, ofrece una experiencia de usuario fluida y profesional.

### ✨ Características

- 🎨 **Diseño Dark Mode** con colores corporativos (rojo y negro)
- 📱 **Totalmente Responsive** - se adapta a móviles, tablets y desktop
- ⚡ **Animaciones Suaves** - efectos de scroll y transiciones fluidas
- 📧 **Formulario de Contacto Funcional** - integrado con EmailJS
- 🔍 **SEO Optimizado** - meta tags y estructura semántica
- ♿ **Accesible** - diseño inclusivo y navegable

---

## 🛠️ Tecnologías Utilizadas

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Servicios

![EmailJS](https://img.shields.io/badge/EmailJS-Email_Service-green?style=for-the-badge)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-Icons-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)

### Herramientas

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 📁 Estructura del Proyecto

```
* **`index.html`** - Contiene la estructura principal del portafolio
* **`docs/`** - Esta adjunto la hoja de vida en formato PDF
* **`assets/`** - Carpeta con recursos estáticos
  * **`images/`** - Imágenes y capturas de pantalla de proyectos
  * **`css/`** - Archivo CSS principal
  * **`js/`** - Archivo JavaScript principal
* **`README.md`** - Documentación del proyecto
```

---

## 🚀 Instalación y Uso

### Opción 1: Ver Online (Recomendado)

Simplemente visita: [Tu URL de GitHub Pages aquí](#)

### Opción 2: Clonar y Ejecutar Localmente

```bash
# Clonar el repositorio
git clone https://github.com/a2-digital/portafolio.git

# Navegar al directorio
cd portafolio

# Abrir con Live Server (VS Code) o directamente abrir index.html
```

**Nota:** No requiere instalación de dependencias. Es HTML/CSS/JS puro.

---

## 📧 Configuración de EmailJS

Para que el formulario de contacto funcione:

1. Crea una cuenta en [EmailJS](https://www.emailjs.com/)
2. Configura un servicio de email (Gmail)
3. Crea un template con estas variables:
   - `{{from_name}}`
   - `{{from_email}}`
   - `{{subject}}`
   - `{{message}}`
4. Actualiza en `index.html`:
   ```javascript
   emailjs.init("TU_PUBLIC_KEY");
   ```
5. Actualiza en `main.js`:
   ```javascript
   emailjs.send("TU_SERVICE_ID", "TU_TEMPLATE_ID", templateParams);
   ```

---

## 📊 Secciones del Portafolio

### 🏠 Inicio (Hero)

- Presentación personal
- Efecto de escritura animado
- Links a redes sociales
- Botones de acción (Ver Proyectos / Descargar CV)

### 👤 Sobre Mí

- Biografía profesional
- Habilidades técnicas (SQL, Python, Power BI, Excel)
- Timeline de experiencia y educación
- Información de contacto

### 💼 Proyectos

Muestra de 4 proyectos principales:

1. **Análisis de Consumo Energético**

   - Python, pandas, matplotlib
   - Análisis exploratorio de datos (EDA)

2. **Análisis de Ventas E-commerce**

   - Python, pandas, matplotlib
   - Análisis exploratorio de datos (EDA)

3. **Sitio Web para Tesis**

   - HTML, CSS, JavaScript, Python, MySql
   - Diseño responsive

4. **Sitio Web de Servicios**
   - HTML, CSS, JavaScript
   - Interfaz moderna

### 📬 Contacto

- Formulario funcional con EmailJS
- Información de contacto directa
- Enlaces a redes sociales

---

## ✨ Funcionalidades Destacadas

### 🎨 Diseño y UX

- **Dark Mode** con paleta de colores corporativa
- **Animaciones al scroll** usando Intersection Observer
- **Navegación smooth scroll** entre secciones
- **Navbar con efecto blur** al hacer scroll
- **Botón scroll-to-top** que aparece dinámicamente

### 📱 Responsive Design

- Grid system flexible
- Menú hamburguesa para móviles
- Imágenes optimizadas
- Breakpoints para tablets y móviles

### ⚡ Performance

- HTML semántico para mejor SEO
- CSS optimizado con variables
- JavaScript vanilla (sin frameworks pesados)
- Lazy loading de imágenes

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usar el código como referencia, pero por favor no copies el contenido personal (textos, proyectos, información personal).

---

## 📞 Contacto

¿Te interesa mi trabajo? ¡Contactemos!

- **Email:** andresdal090@gmail.com
- **LinkedIn:** [Andrés Aranguren](https://www.linkedin.com/in/andres-aranguren-b758a3211)
- **GitHub:** [@a2-digital](https://github.com/a2-digital)
- **Ubicación:** Bogotá, Colombia

---

## 🙏 Agradecimientos

- [Font Awesome](https://fontawesome.com/) - Iconos
- [EmailJS](https://www.emailjs.com/) - Servicio de email
- [Google Fonts](https://fonts.google.com/) - Tipografías
- [GitHub Pages](https://pages.github.com/) - Hosting

---

<div align="center">

### ⭐ Si te gustó este portafolio, dale una estrella!

**Desarrollado con ❤️ por Andrés Aranguren**

© 2025 - Todos los derechos reservados

</div>
