# Ejercicios de JavaScript

Este proyecto contiene una colección de 6 ejercicios interactivos desarrollados en JavaScript vanilla, cada uno diseñado para demostrar diferentes conceptos de programación y manipulación del DOM.

## 📋 Contenido

1. [Juego: Adivina el Número](#1-juego-adivina-el-número)
2. [Clase Persona](#2-clase-persona)
3. [Lista de Tareas](#3-lista-de-tareas)
4. [Reloj Digital](#4-reloj-digital)
5. [Cronómetro](#5-cronómetro)
6. [Temporizador](#6-temporizador)

## 🎯 Ejercicios

### 1. Juego: Adivina el Número

**Descripción:** Un juego interactivo donde el usuario debe adivinar un número aleatorio entre 1 y 100.

**Funcionalidades:**
- Generación de número aleatorio
- Feedback al usuario (mayor/menor)
- Validación de entrada
- Reinicio automático al ganar

**Tecnologías utilizadas:**
- `Math.random()` para generar números aleatorios
- `parseInt()` para validación de entrada
- Manipulación del DOM con `getElementById()`

### 2. Clase Persona

**Descripción:** Implementación de una clase que modela una persona con varios métodos para mostrar información generacional y personal.

**Funcionalidades:**
- Constructor con múltiples propiedades
- Método `mostrarGeneracion()`: Determina la generación basada en el año de nacimiento
- Método `esMayorDeEdad()`: Verifica si es mayor de edad
- Método `mostrarDatos()`: Muestra toda la información personal
- Formulario interactivo para crear instancias

**Generaciones incluidas:**
- Silent Generation (1930-1948)
- Baby Boomer (1949-1968)
- Generación X (1969-1980)
- Generación Y - Millennials (1981-1993)
- Generación Z (1994-2010)
- Generación Alpha (2011+)

### 3. Lista de Tareas

**Descripción:** Una aplicación simple de gestión de tareas con funcionalidades básicas de CRUD.

**Funcionalidades:**
- Agregar nuevas tareas
- Eliminar tareas individualmente
- Interfaz responsive con Bootstrap
- Validación de entrada vacía

**Tecnologías utilizadas:**
- `createElement()` para crear elementos dinámicamente
- Event listeners para manejo de eventos
- Bootstrap para estilos

### 4. Reloj Digital

**Descripción:** Un reloj digital que muestra la fecha y hora actual en tiempo real.

**Funcionalidades:**
- Actualización automática cada segundo
- Formato de fecha completo (día de la semana, día, mes, año)
- Formato de hora HH:MM:SS
- Inicio/parada automática según la vista activa

**Tecnologías utilizadas:**
- `setInterval()` para actualizaciones periódicas
- Objeto `Date()` para obtener fecha/hora
- Arrays para nombres de días y meses
- Template literals para formateo

### 5. Cronómetro

**Descripción:** Un cronómetro con funcionalidades de inicio, pausa y reset.

**Funcionalidades:**
- Conteo ascendente en formato HH:MM:SS
- Botones de control: Iniciar, Pausar, Reset
- Formato de tiempo con ceros iniciales
- Estado persistente entre pausas

**Tecnologías utilizadas:**
- `setInterval()` para el conteo
- Variables globales para mantener estado
- Lógica de tiempo con conversiones automáticas

### 6. Temporizador

**Descripción:** Un temporizador de cuenta regresiva configurable por el usuario.

**Funcionalidades:**
- Configuración de tiempo en segundos
- Cuenta regresiva en formato MM:SS
- Notificación al finalizar
- Controles de inicio, pausa y reset
- Validación de entrada

**Tecnologías utilizadas:**
- `Math.floor()` para conversiones de tiempo
- Operador módulo (%) para cálculos
- Validación con `isNaN()`

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/Cdantequera/EjJS5.git]
   cd ejercicios-javascript
   ```

2. **Abrir en el navegador:**
   - Abrir el archivo `index.html` en cualquier navegador web moderno
   - No requiere servidor web ni dependencias adicionales

3. **Navegación:**
   - Usar el menú de navegación para cambiar entre ejercicios
   - Cada ejercicio es independiente y funcional

## 📁 Estructura del Proyecto

```
proyecto/
├── index.html          # Página principal con navegación
├── script.js          # Archivo principal con toda la lógica
├── styles.css         # Estilos personalizados (opcional)
└── README.md          # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica
- **CSS3/Bootstrap:** Estilos y diseño responsive
- **JavaScript ES6+:** Lógica de aplicación
  - Clases y métodos
  - Arrow functions
  - Template literals
  - Destructuring
  - Operadores ternarios

## 📝 Características Técnicas

- **Sin dependencias externas:** JavaScript vanilla únicamente
- **Responsive Design:** Compatible con dispositivos móviles
- **Accesibilidad:** Uso de elementos semánticos HTML
- **Validación de datos:** Manejo de errores y entradas inválidas
- **Gestión de memoria:** Limpieza adecuada de intervalos

## 🎨 Funcionalidades Destacadas

### Sistema de Navegación
- Función `mostrarEjercicio()` que controla la visibilidad de contenedores
- Gestión automática del reloj según la vista activa
- Interfaz única sin recarga de página

### Manejo de Eventos
- Event listeners eficientes
- Validación en tiempo real
- Feedback inmediato al usuario

### Gestión de Tiempo
- Tres implementaciones diferentes de tiempo:
  - Reloj en tiempo real
  - Cronómetro ascendente
  - Temporizador descendente

## 🔧 Personalización

El código está estructurado para facilitar modificaciones:

- **Estilos:** Modificar clases CSS existentes o agregar nuevas
- **Funcionalidades:** Cada ejercicio es modular e independiente
- **Validaciones:** Fácil extensión de reglas de validación
- **Tiempos:** Intervalos configurables en cada función


Este proyecto está abierto a contribuciones. Algunas ideas para mejoras:

- Agregar más ejercicios
- Implementar localStorage para persistencia
- Mejorar la interfaz de usuario
- Agregar animaciones CSS
- Implementar tests unitarios
- Traducción a otros idiomas

## 👨‍💻 Autor Daniel Antequera

Desarrollado como ejercicios de práctica para aprender JavaScript moderno y manipulación del DOM.
