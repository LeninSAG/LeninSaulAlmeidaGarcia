# LeninSaulAlmeidaGarcia
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Pagina Web</title>
</head>
<body>
    <h1>Hola mundo</h1>
    <h2>Hola mundo, esta es mi primera pagina Web 2</h2>
    <p>En la actualidad, las <strong>páginas web</strong> se han convertido en una <em>herramienta fundamental</em> para el <mark>éxito empresarial en la era digital</mark>. <blockquote>La creciente dependencia de la tecnología y la expansión del uso de internet han hecho que las empresas deban adaptarse a esta nueva realidad y aprovechar las oportunidades que ofrece el mundo digital para garantizar su crecimiento y <small>consolidación </small>en el mercado</blockquote>.</p> <br>
    </p>
    <br/>
    <a href="https://utb.edu.ec/content-2490" target="_blank">Ir al Sitio</a> <br> 
   <img src="aiowa.png" alt="Imagen" width="300">
<nav>
    <a href="https://ec.linkedin.com/in/lenin-saul-almeida-garcia-12a8a6213">Sobre mí</a>
</nav>
<section id="sobremi">
    <h2>Estudiante</h2>
    <p>Hola soy estudiante de la Universidad Tecnica de Babahoyo<strong>Tu Nombre</strong>. Soy un <em>profesional</em> en <mark>tu área de especialización</mark>.</p>
</section>
<section id="intereses">
    <h2>Intereses</h2>
    <ul>
        <li>Estudiar </li>
        <li>Aprende </li>
        <li>Ser profesional </li>
    </ul>
</section>
<section id="habilidades">
    <h2>Habilidades</h2>
    <table>
        <thead>
            <tr>
                <th>Habilidad</th>
                <th>Nivel</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>HTML</td>
                <td>Avanzado</td>
            </tr>
            <tr>
                <td>CSS</td>
                <td>Intermedio</td>
            </tr>
            <tr>
                <td>JavaScript</td>
                <td>Intermedio</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="2">Total de habilidades: 3</td>
            </tr>
        </tfoot>
    </table>
</section>
<section id="contacto">
    <h2>Contacto</h2>
    <form action="#" method="post">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre" required><br>
        <label for="correo">Correo:</label><br>
        <input type="email" id="correo" name="correo" required><br>
        <label for="edad">Edad:</label><br>
        <input type="number" id="edad" name="edad" min="1" required><br>
        <label for="genero">Género:</label><br/>
        <select id="genero" name="genero" required>
            <option value="masculino">Masculino</option>
            <option value="femenino">Femenino</option>
        </select><br>
        <label for="intereses">Intereses:</label><br>
        <textarea id="intereses" name="intereses" required></textarea><br>
        <label for="comentarios">Comentarios:</label><br>
        <textarea id="comentarios" name="comentarios" required></textarea><br>
        <input type="submit" value="Enviar">
    </form>
</section>
<footer>
    <p>&copy; <span id="year"></span> Tu Nombre. Todos los derechos reservados.</p>
    <p>
        <a href="https://facebook.com" target="_blank">Facebook</a> |
        <a href="https://twitter.com" target="_blank">Twitter</a>
    </p>
</footer>
<script>
// Opcional: Código JavaScript para mostrar el año actual en el footer
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>