# Taller 18 - Grpo 03

## Descripción del Proyecto
Este proyecto es una aplicación creada con React utilizando Vite como herramienta de construcción. Contiene cinco componentes personalizados que son invocados dentro del componente principal de la aplicación.

### Objetivos
1. Aprender y aplicar conceptos básicos sobre props en React.
2. Explorar diversas formas de estilizar componentes en React.
3. Practicar la creación de un proyecto estructurado con componentes reutilizables.

---

## Contenido del Proyecto

### 1. Conceptos básicos trabajados
- **Props en React:**
  Los props (abreviatura de "properties") son argumentos que se pasan a los componentes de React. Sirven para transferir datos de un componente padre a un componente hijo, permitiendo que los componentes sean reutilizables y dinámicos.

- **Estilos en React:**
  Existen varias maneras de aplicar estilos a los componentes:
  - Estilos en línea (inline styles): Se pasan como objetos a través de la propiedad `style`.
  - Archivos CSS: Se importa un archivo `.css` y se aplica una clase al componente mediante `className`.
  - CSS Modules: Se utilizan para evitar conflictos de nombres de clases.
  - Librerías de estilos: Frameworks como Tailwind CSS, Styled-Components o Emotion para un diseño más dinámico.

### 2. Implementación del Proyecto
#### Herramientas utilizadas
- **Vite:** Para inicializar el proyecto con una configuración rápida y optimizada.
- **React:** Librería principal para construir la interfaz de usuario.

#### Estructura del Proyecto
```plaintext
/src
  /components
    Header.jsx
    Footer.jsx
    Sidebar.jsx
    MainContent.jsx
    Card.jsx
  App.jsx
  main.jsx
```

#### Descripción de Componentes
1. **Header:** Encabezado principal de la aplicación.
2. **Footer:** Pie de página que incluye información de copyright.
3. **Sidebar:** Barra lateral con opciones de navegación.
4. **MainContent:** Contenedor principal que muestra el contenido principal de la aplicación.
5. **Card:** Un componente reutilizable que muestra una tarjeta con información dinámica usando props.

### 3. Instrucciones de Uso
#### Instalación
1. Clona este repositorio.
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Accede al directorio del proyecto.
   ```bash
   cd <NOMBRE_DEL_DIRECTORIO>
   ```
3. Instala las dependencias.
   ```bash
   npm install
   ```

#### Ejecución
Inicia el servidor de desarrollo.
```bash
npm run dev
```
Accede a la aplicación en tu navegador en `http://localhost:5173`.

---

## Conclusión
Este proyecto sirvió como práctica para consolidar conceptos clave de React como el uso de props y diversas formas de estilizar componentes, además de fortalecer habilidades en la creación y estructuración de un proyecto usando Vite.
