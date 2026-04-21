# Portafolio apuntes

**Estructura base para un portafolio:**

- index.html
- style.css
- script.js

## HTML --> index.html --> estructura del sitio

- aquí se define la estructura del sitio: textos, secciones e imágenes
- que es lo qué hay en la página

**ejemplo**

```cpp
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Portafolio de Valentina</title>

    <!-- Conexión con CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Valentina Ruz</h1>
        <p>Diseño + Tecnología</p>
    </header>

    <section id="sobre-mi">
        <h2>Sobre mí</h2>
        <p>Soy diseñadora interesada en robótica e interacción.</p>
    </section>

    <section id="proyectos">
        <h2>Proyectos</h2>
        <div class="proyecto">
            <h3>Silla ergonómica</h3>
            <p>Rediseño de mobiliario universitario.</p>
        </div>
    </section>

    <button onclick="saludo()">Haz click</button>

    <!-- Conexión con JS -->
    <script src="script.js"></script>

</body>
</html>
```

## CSS --> style.css --> diseño visual

- aquí se define colores, tipografía, layouts, etc.
- al final es cómo se ve en la página

**ejemplo**

```cpp
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
}

header {
    background-color: black;
    color: white;
    text-align: center;
    padding: 20px;
}

section {
    padding: 20px;
}

.proyecto {
    background: white;
    margin: 10px 0;
    padding: 10px;
    border-radius: 10px;
}
```

## JS --> script.js --> JavaScript --> interacción

- aquí es lo que quieras que pase, como botones, animaciones
- que es lo qué hace la página

**ejemplo**

```cpp
function saludo() {
    alert("Hola, este es mi portafolio 🚀");
}
```

---

## Como subirlo a Github

Ir a:

1. Settings → Pages
2. Activar GitHub Pages
3. Te dará un link tipo:
   
> https://tuusuario.github.io/portafolio/

