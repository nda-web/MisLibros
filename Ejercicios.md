# **Desarrollo Web Desde Cero: Creando tu Propio Blog con HTML, CSS y JavaScript**

**Autor:** Martín Alejandro Oviedo  
**Coautor:** Daedalus  
**Fecha de Publicación:** 2024  



## Ejercicios

### Capítulo 1: Fundamentos de HTML

1. **Estructura de un Documento HTML**  
   Crea un archivo `index.html` que contenga la estructura básica de un documento HTML. Asegúrate de incluir un título, un encabezado y un párrafo de texto.

2. **Etiquetas y Listas**  
   Agrega una lista desordenada a tu documento HTML con al menos cinco elementos. Luego, crea una lista ordenada con al menos tres elementos.

3. **Formularios**  
   Crea un formulario simple que contenga campos para el nombre, el correo electrónico y un mensaje. Asegúrate de incluir etiquetas adecuadas para cada campo.

### Capítulo 2: Introducción a CSS y Frameworks Relacionados

1. **Aplicación de Estilos Básicos**  
   Crea un archivo `styles.css` y vincúlalo a tu `index.html`. Aplica estilos básicos a los elementos, como color de fondo, colores de texto y márgenes.

2. **Uso de Clases y IDs**  
   Modifica tu HTML para incluir clases e IDs. Crea reglas CSS en `styles.css` para aplicar estilos diferentes a elementos con clases y IDs específicos.

3. **Diseño Responsivo con Media Queries**  
   Utiliza media queries para hacer que tu diseño sea responsivo. Crea estilos que cambien según el ancho de la pantalla.

### Capítulo 3: Introducción a Bootstrap 5

1. **Crear una Página con Bootstrap**  
   Crea una nueva página `bootstrap.html` e incluye Bootstrap mediante CDN. Utiliza el sistema de cuadrícula de Bootstrap para crear un diseño con al menos tres columnas.

2. **Componentes de Bootstrap**  
   Añade una barra de navegación y un par de tarjetas utilizando los componentes de Bootstrap. Asegúrate de que las tarjetas contengan imágenes, títulos y descripciones.

### Capítulo 4: Construcción del Front-End del Blog

1. **Página de Inicio**  
   Diseña la página de inicio de tu blog utilizando los componentes de Bootstrap. Incluye una barra de navegación, una sección de encabezado y un área para mostrar entradas del blog.

2. **Formulario de Entradas de Blog**  
   Crea un formulario que permita a los usuarios ingresar nuevas entradas para el blog. Asegúrate de incluir validaciones de entrada.

### Capítulo 5: Introducción a JavaScript para Interactividad

1. **Manipulación del DOM**  
   Escribe un script que modifique el contenido de tu página de inicio. Por ejemplo, cambia el texto de un encabezado o agrega un nuevo párrafo al contenido.

2. **Eventos y Funciones**  
   Crea un botón que, al hacer clic, muestre un mensaje de alerta. Asegúrate de usar `addEventListener` para manejar el evento.

### Capítulo 6: Manejo de la Base de Datos con JSON

1. **Simulación de una Base de Datos**  
   Crea un archivo `entradas.json` que contenga al menos tres entradas de blog en formato JSON.

2. **Carga de Datos JSON**  
   Escribe un script que cargue los datos del archivo `entradas.json` y los muestre en tu página web, utilizando la manipulación del DOM.

### Capítulo 7: Integración Completa

1. **Agregar y Mostrar Entradas**  
   Implementa la funcionalidad para agregar nuevas entradas al blog utilizando los datos ingresados en el formulario. Asegúrate de que las nuevas entradas se muestren automáticamente en la página.

2. **Editar y Eliminar Entradas**  
   Agrega botones de edición y eliminación junto a cada entrada del blog. Implementa la lógica necesaria para editar el contenido o eliminar una entrada del DOM.

### Capítulo 8: Mejoras y Seguridad

1. **Validación de Formularios**  
   Mejora la validación de tu formulario de entradas para asegurarte de que los campos no estén vacíos y que los datos ingresados sean correctos.

2. **Pruebas de Seguridad**  
   Investiga y documenta al menos tres buenas prácticas de seguridad que debes implementar en tu blog para protegerlo contra inyecciones de código y otros ataques.

### Capítulo 9: Despliegue del Blog

1. **Despliegue en GitHub Pages**  
   Sube tu proyecto a un nuevo repositorio de GitHub y configura GitHub Pages para que tu blog sea accesible en línea.

2. **Optimización**  
   Realiza pruebas de velocidad y optimización utilizando herramientas como Google PageSpeed Insights. Implementa las recomendaciones para mejorar el rendimiento de tu blog.

### Capítulo Oculto: Trucos y Consejos

1. **Documentación de Código**  
   Revisa tu código y agrega comentarios donde sea necesario para mejorar la legibilidad y el mantenimiento.

2. **Accesibilidad**  
   Implementa al menos dos mejoras de accesibilidad en tu blog, como texto alternativo para imágenes y un menú de navegación accesible.



---

## Ejercicios y Respuestas

### Capítulo 1: Fundamentos de HTML

1. **Estructura de un Documento HTML**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primer Documento HTML</title>
</head>
<body>
    <h1>Bienvenido a Mi Blog</h1>
    <p>Este es un párrafo de ejemplo en mi primer documento HTML.</p>
</body>
</html>
```

2. **Etiquetas y Listas**

```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    <li>Elemento 3</li>
    <li>Elemento 4</li>
    <li>Elemento 5</li>
</ul>

<ol>
    <li>Primer Elemento</li>
    <li>Segundo Elemento</li>
    <li>Tercer Elemento</li>
</ol>
```

3. **Formularios**

```html
<form>
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="email">Correo Electrónico:</label>
    <input type="email" id="email" name="email" required>

    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="mensaje" required></textarea>

    <button type="submit">Enviar</button>
</form>
```

### Capítulo 2: Introducción a CSS y Frameworks Relacionados

1. **Aplicación de Estilos Básicos** (Archivo `styles.css`)

```css
body {
    background-color: #f0f0f0;
    color: #333;
    font-family: Arial, sans-serif;
}

h1 {
    color: #2c3e50;
}

p {
    margin: 20px 0;
}
```

2. **Uso de Clases y IDs**

```html
<style>
    .mi-clase {
        color: #3498db;
    }

    #mi-id {
        font-weight: bold;
    }
</style>

<p class="mi-clase">Este es un párrafo con una clase.</p>
<p id="mi-id">Este es un párrafo con un ID.</p>
```

3. **Diseño Responsivo con Media Queries**

```css
@media (max-width: 600px) {
    body {
        background-color: #ecf0f1;
    }
}
```

### Capítulo 3: Introducción a Bootstrap 5

1. **Crear una Página con Bootstrap**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css">
    <title>Bootstrap Page</title>
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-md-4">Columna 1</div>
            <div class="col-md-4">Columna 2</div>
            <div class="col-md-4">Columna 3</div>
        </div>
    </div>
</body>
</html>
```

2. **Componentes de Bootstrap**

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Mi Blog</a>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Inicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Entradas</a>
            </li>
        </ul>
    </div>
</nav>

<div class="card" style="width: 18rem;">
    <img src="entrada1.jpg" class="card-img-top" alt="Entrada 1">
    <div class="card-body">
        <h5 class="card-title">Título de la Entrada</h5>
        <p class="card-text">Descripción de la entrada del blog.</p>
        <a href="#" class="btn btn-primary">Leer más</a>
    </div>
</div>
```

### Capítulo 4: Construcción del Front-End del Blog

1. **Página de Inicio**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css">
    <title>Mi Blog</title>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Mi Blog</a>
    </nav>

    <header class="bg-primary text-white text-center p-5">
        <h1>Bienvenido a Mi Blog</h1>
        <p>Explora contenido interesante sobre tecnología y desarrollo web.</p>
    </header>

    <div class="container mt-5" id="entradasContainer">
        <!-- Las entradas del blog se mostrarán aquí -->
    </div>

    <script src="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

2. **Formulario de Entradas de Blog**

```html
<form id="formAgregarEntrada" class="mt-5">
    <div class="mb-3">
        <label for="titulo" class="form-label">Título</label>
        <input type="text" class="form-control" id="titulo" name="titulo" required>
    </div>
    <div class="mb-3">
        <label for="contenido" class="form-label">Contenido</label>
        <textarea class="form-control" id="contenido" name="contenido" rows="5" required></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Publicar</button>
</form>
```

### Capítulo 5: Introducción a JavaScript para Interactividad

1. **Manipulación del DOM**

```html
<script>
document.addEventListener('DOMContentLoaded', function() {
    document.getElementById('titulo').innerText = "Nuevo Título del Blog";
});
</script>
```

2. **Eventos y Funciones**

```html
<button id="miBoton">Clic aquí</button>

<script>
document.getElementById("miBoton").addEventListener("click", function() {
    alert("¡Botón clicado!");
});
</script>
```

### Capítulo 6: Manejo de la Base de Datos con JSON

1. **Simulación de una Base de Datos** (Archivo `entradas.json`)

```json
[
    {
        "id": 1,
        "titulo": "Mi Primer Post",
        "autor": "Juan Pérez",
        "contenido": "Este es el contenido de mi primer post.",
        "fecha": "2024-11-07"
    },
    {
        "id": 2,
        "titulo": "Segundo Post",
        "autor": "Ana Gómez",
        "contenido": "Aquí está el contenido del segundo post.",
        "fecha": "2024-11-08"
    }
]
```

2. **Carga de Datos JSON**

```html
<script>
fetch('entradas.json')
    .then(response => response.json())
    .then(data => {
        const container = document.getElementById('entradasContainer');
        container.innerHTML = ''; // Limpiar el contenedor
        data.forEach(entrada => {
            let card = `
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">${entrada.titulo}</h5>
                            <p class="card-text">${entrada.contenido}</p>
                            <p class="card-text"><small class="text-muted">${entrada.fecha}</small></p>
                        </div>
                    </div>
                </div>
            `;
            container.innerHTML += card;
        });
    })
    .catch(error => console.error('Error al cargar las entradas:', error));
</script>
```

### Capítulo 7: Integración Completa

1. **Agregar y Mostrar Entradas**

```html
<script>
document.getElementById('formAgregarEntrada').addEventListener('submit', function(event) {
    event.preventDefault();
    let titulo = document.getElementById('titulo').value;
    let contenido = document.getElementById('contenido').value;

    agregarEntrada(titulo, contenido);
});

function agregarEntrada(titulo, contenido) {
    const nuevaEntrada = {
        id: Date.now(),
        titulo: titulo,
        contenido: contenido,
        fecha: new Date().toISOString().split('T')[0]
    };

    // Simulación de agregar la entrada

 a un "servidor"
    console.log(JSON.stringify(nuevaEntrada));
    cargarEntradas(); // Recargar las entradas para ver la nueva entrada
}
</script>
```

2. **Editar y Eliminar Entradas**

```html
// Función para eliminar una entrada
function eliminarEntrada(id) {
    console.log(`Eliminar entrada con ID: ${id}`);
    cargarEntradas(); // Recargar las entradas después de eliminar
}
```

### Capítulo 8: Mejoras y Seguridad

1. **Validación de Formularios**

```html
<script>
function validarEntrada(titulo, contenido) {
    if (titulo.length < 5) {
        alert("El título debe tener al menos 5 caracteres.");
        return false;
    }
    if (contenido.length < 20) {
        alert("El contenido debe tener al menos 20 caracteres.");
        return false;
    }
    return true;
}
</script>
```

2. **Pruebas de Seguridad**  
   (Documenta tres buenas prácticas)

- Validar y sanitizar entradas del usuario.
- Usar HTTPS para proteger la comunicación.
- Implementar políticas de control de acceso adecuadas.

### Capítulo 9: Despliegue del Blog

1. **Despliegue en GitHub Pages**  
   (Sigue los pasos descritos anteriormente en el capítulo.)

2. **Optimización**  
   (Usa herramientas como Google PageSpeed Insights y aplica las recomendaciones.)

### Capítulo Oculto: Trucos y Consejos

1. **Documentación de Código**  
   (Ejemplo de cómo añadir comentarios)

```javascript
// Esta función carga las entradas del blog desde el archivo JSON
function cargarEntradas() {
    // Lógica para obtener datos
}
```

2. **Accesibilidad**  
   (Implementa mejoras en tu HTML)

```html
<img src="imagen.jpg" alt="Descripción de la imagen" />
```

---

