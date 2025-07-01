<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Liderazgo y Gestión de Equipos</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto&display=swap');

    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #ffffff;
    }

    header {
      background: linear-gradient(90deg, #00c6ff, #0072ff);
      color: white;
      padding: 40px 20px;
      text-align: center;
      font-family: 'Orbitron', sans-serif;
      text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
    }

    nav {
      background-color: #121212;
      padding: 12px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 0 12px rgba(0, 255, 255, 0.3);
    }

    nav a {
      color: #0ff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #fff;
    }

    section {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(8px);
      margin: 30px auto;
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 1000px;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
    }

    h2 {
      color: #0ff;
      font-family: 'Orbitron', sans-serif;
    }

    h3 {
      color: #00ffe7;
      margin-top: 20px;
    }

    p {
      color: #e0e0e0;
      line-height: 1.6;
    }

    .integrante {
      display: flex;
      align-items: center;
      margin-bottom: 30px;
      background-color: rgba(255, 255, 255, 0.05);
      padding: 15px;
      border-radius: 12px;
      box-shadow: inset 0 0 10px rgba(0, 255, 255, 0.1);
    }

    .integrante img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-right: 20px;
      border: 2px solid #0ff;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      background-color: rgba(255, 255, 255, 0.03);
    }

    th,
    td {
      border: 1px solid #00c6ff;
      padding: 12px;
      color: #fff;
    }

    thead {
      background-color: rgba(0, 198, 255, 0.3);
    }

    footer {
      background-color: #000;
      color: #0ff;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
      font-family: 'Orbitron', sans-serif;
      letter-spacing: 1px;
    }

    #NO\ TOCAR {
      border: 2px dashed red;
      background-color: rgba(255, 0, 0, 0.1);
      color: #ff8080;
    }

    /* Agrega transiciones para toggles */
    [id^="subtemas"] {
      transition: all 0.5s ease;
    }

    h2[onclick] {
      transition: color 0.3s ease;
    }

    h2[onclick]:hover {
      color: #ffffff;
      cursor: pointer;
    }
  </style>
</head>

    <header>
        <h1>Liderazgo y Gestión de Equipos </h1>
    </header>

    <section id="inicio">
        <h2>Presentación del Curso</h2>
        <p>El curso de <strong>Liderazgo y Gestión de Equipos</strong> nos enseña a identificar los elementos clave para liderar con efectividad, resolver conflictos, fomentar el trabajo colaborativo y desarrollar habilidades de comunicación dentro de una organización o proyecto.</p>
        <p>Durante este curso, hemos aprendido técnicas esenciales para dirigir equipos, establecer objetivos comunes y desarrollar un entorno de confianza y compromiso.</p>
    </section>

    <section id="integrantes">
        <h2>Integrantes</h2>
        <p>Somos un equipo de trabajo de 4 integrantes. Cada uno responde:</p>
        <p><strong>¿Cuál es la importancia del curso de Liderazgo y Gestión de Equipos?</strong></p>
        <p><strong>¿En qué aplicarías lo aprendido?</strong></p>

        <div class="integrante">
            <img src="https://media.tenor.com/OXMS-QvUMk0AAAAe/jerry.png" alt="Foto integrante 1">
            <div>
                <p><strong>Nombre:</strong> Donayre Carhuayo Luis Erasmo</p>
                <p><strong>Código:</strong> U24208041</p>
                <p>"Link del video respondiendo a las preguntas"</p>
            </div>
        </div>

        <div class="integrante">
            <img src="https://media.tenor.com/OXMS-QvUMk0AAAAe/jerry.png" alt="Foto integrante 2">
            <div>
                <p><strong>Nombre:</strong> Mayo Pecho Alejandra Valentina </p>
                <p><strong>Código:</strong> U23206468</p>
                <p>"Link del video respondiendo a las preguntas"</p>
            </div>
        </div>

        <div class="integrante">
            <img src="https://media.tenor.com/OXMS-QvUMk0AAAAe/jerry.png" alt="Foto integrante 3">
            <div>
                <p><strong>Nombre:</strong> Gorddy Vinces Yaren Munaya Euribe</p>
                <p><strong>Código:</strong> U23249183</p>
                <p>"Link del video respondiendo a las preguntas"</p>
            </div>
        </div>

        <div class="integrante">
            <img src="https://media.tenor.com/OXMS-QvUMk0AAAAe/jerry.png" alt="Foto integrante 4">
            <div>
                <p><strong>Nombre:</strong> Anyelo Efrain Palomino Champe</p>
                <p><strong>Código:</strong> U23249209</p>
                <p>"Link del video respondiendo a las preguntas"</p>
            </div>
        </div>
    </section>

    <section id="unidad1">
        <h2 onclick="toggleSubtema('subtemas1')" style="cursor:pointer;">Unidad 1: El papel del equipo en las organizaciones modernas</h2>
        <div id="subtemas1" style="display: none; margin-left: 20px;">
            <h3>1.1 ¿Qué es ser un liderazgo autentico?</h3>
            <p>Un líder auténtico implica ser genuino, es decir, personificar el verdadero yo y dejar a un lado el ego. Al ser auténtico, el líder recurre siempre a su sistema de valores, principios, moral y creencias para actuar. No oculta sus debilidades, sino que trabaja en mejorarlas; no exagera sus fortalezas, pero sabe obtener el mejor provecho de ellas.</p>


            <h3>1.2 Diferencia entre jefe y lider</h3>
            <table style="width: 100%; border-collapse: collapse; margin-top: 10px;">
                <thead style="background-color: #dfefff;">
                    <tr>
                        <th style="border: 1px solid #ccc; padding: 10px;">Personaje</th>
                        <th style="border: 1px solid #ccc; padding: 10px;">Diferencias</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td style="border: 1px solid #ccc; padding: 10px;">Lider</td>
                        <td style="border: 1px solid #ccc; padding: 10px;">
                            <p>- Genera entusiasmo </p>
                            <p>- Busca soluciones a los problemas </p>
                            <p>- Pide ayuda</p>- Pide ayuda
                            <p>- Dice "Nosotros"</p>
                            <p>- Comparte exitos</p>
                        </td>

                    </tr>
                    <tr>
                        <td style="border: 1px solid #ccc; padding: 10px;">Jefe</td>
                        <td style="border: 1px solid #ccc; padding: 10px;">
                            <p>- Inspira respeto</p>
                            <p>- Busca responsable de los problemas</p>
                            <p>- Da ordenes</p>
                            <p>- Dice "yo"</p>
                            <p>- Presume los exitos</p>
                        </td>
                    </tr>

                </tbody>
            </table>

            <h3>1.3 ¿Cómo ser un lider autentico?</h3>
            <p> Ten una visión: La clave principal para ser un líder es tener un propósito en mente, peor no basta con un simple propósito, necesitas desarrollar una visión clara de lo que quieres alcanzar.</p>
            <p>  Transmite tu pasión: Un verdadero líder se apasiona mucho por lograr esa visión, que inevitablemente contagia a todo su equipo.</p>
            <p> Se autentico: Tienes que ser tu mismo y dejar que los demás te conozcan tal y como eres y no trates de aparentar ser algo que no eres.</p>
            <p> Comprométete de corazón: Tu anhelo mas profundo viene de tu corazón, pero si no tienes compromiso, lo dejaras tirado en el camino. Siempre debes ser consistente con lo que dices y haces, mientras cumples tus promesas. </p>
            <p> Gana su confianza: Demuestra que sabes realmente lo que haces y que realmente quieres ayudar a las personas.</p>
            <p> Crece con humildad: Mantente en constate aprendizaje, no creas que eres el mejor o perderás todo tu liderazgo.</p>
            <p> Motiva a tu equipo: El trabajo en equipo y la motivación constante son claves fundamentales en el éxito de cualquier proyecto.</p>
            <p> Comunícate con precisión: En muchos casos los problemas se generan por una mala comunicación, por eso debes ser preciso y claro con tus palabras, siempre preguntando para así poder asegurar ide que fuiste comprendido.</p>
            <p> Crea autoridad por admiración: Comparte tu historia para inspirar, para que ellos te digan “yo quiero lograr lo que tu has logrado, por lo tanto, voy a seguir tus pasos”</p>
            <p> Crea nuevos líderes: Tu verdadero objetivo como un líder autentico es hacer de tus seguidores nuevos lideres.</p>
            <p></p>
            <h3>1.4 Tipo de Liderazgo Etico</h3>
            <p>Es cuando los lideres empresariales demuestran una conducta adecuada, de acuerdo con sus principios y valores reconocidos, tanto dentro como fuera de la oficina </p>
            <p></p>
            <h3>1.5 Rasgos de los Lideres Eticos</h3>
            <p> Da un gran ejemplo: Debes inspirar desde el hacer, no solo el decir, así todo el equipo seguirá tu ejemplo. Los lideres éticos tendrían altos estándares para su equipo, los mismos estándares que establecen para si mismos a diriarios </p>
            <p> Respeta a todos por igual: Tener respeto por los demás de manera equitativa en el equipo y en la empresa. Se debe escuchar atentamente las opiniones y comentarios de todos los integrantes del equipo y/o empresa.</p>
            <p> Comunicación abierta: Se debe tener una buena comunicación para evitar mal entendidos y problemas futuros y así construir confianza y respeto mutuo.</p>
            <p> Mediación justa: Mostrar equidad, escuchar a ambos lados por igual y encontrar soluciones que satisfagan a ambas partes en esencial.</p>
            <p> Se adapta al cambio: El liderazgo ético trata de comprender los cambios, escuchar las preocupaciones, pero también tomar decisiones que deben tomarse y ser respetadas por todo el equipo.</p>
            <p> Tolerancia cero a las violaciones éticas: Los lideres éticos se responsabilizan diariamente ante cualquier problema, por lo tanto, se trata de hacer lo correcto en los momentos indicados, no cuando sea conveniente o cuando alguien este mirando.</p>
            <p></p>
            <h3>1.6 Valores de Lideres</h3>
            <p>• Valentía: Enfrentan los retos y no se intimidan con nada.</p>
            <p>• Pasión: Sienten amor por lo que hacen, motivan y contagian.</p>
            <p>• Honestidad: Siempre es transparente y sus acciones sus acciones están basadas en sus palabras.</p>
            <p>• Trabajo en equipo: Comparten conocimiento, creatividad, saben delegar, aprender mutuamente y orientan.</p>
            <p>• Responsabilidad: Asumen riesgos y los resultados, aunque no sean positivos.</p>
            <p>• Comunicación: Dejan en claro sus objetivos ante los demás y generan confianza.</p>
        </div>
    </section>

    <section id="unidad2">
        <h2 onclick="toggleSubtema('subtemas2')" style="cursor:pointer;">Unidad 2: Las Dinamicas de Grupo</h2>
        <div id="subtemas2" style="display: none; margin-left: 20px;">
            <h3>2.1 Concepto: </h3>
            <p>Las dinámicas de grupo son técnicas y estrategias utilizadas para mejorar la interacción y el desempeño de los equipos en distintos entornos. </p>
            <h3>2.2 Caracteristicas: </h3>
            <p>-	Interacción grupal: Define como los miembros del equipo van a interactuar, compartir ideas y construir conocimiento colaborativamente. </p>
            <p>-	Roles dentro del grupo: Existen roles formales e informales dentro de un equipo, como líder, facilitador, mediador o innovador.</p>
            <p>-	Cohesión del equipo: Es la capacidad del grupo para mantenerse unido influye en su rendimiento y satisfacción.</p>
            <p>-	Toma de decisiones grupal: Los equipos se reúnen para evaluar decisiones grupales, se pueden tomar por consenso, votación o delegación, lo que impacta la eficiencia y compromiso.</p>
            <p>-	Resolución de conflictos: Se trata de solucionar las situaciones problemáticas junto con todo el equipo de trabajo, aplicando estrategias como la mediación y negociación, para así facilitar la armonía en grupo.</p>
            <p>-	Trabajo colaborativo: Se distribuye las tareas según sus habilidades y así potenciar el esfuerzo en conjunto.</p>
            <p>-	Influencia del liderazgo: Un liderazgo efectivo guía al grupo hacia sus objetivos de manera organizada. </p>
            <h3>2.3 Aplicación: </h3>
            <p>1.	Educación: Trabajo en equipo, aprendizaje colaborativo. </p>
            <p>2.	Empresas: Gestión de proyectos y toma de decisiones.</p>
            <p>3.	Desarrollo de software: Equipos ágiles y metodologías SCRUM.</p>
            <p>4.	Investigación: Colaboración interdisciplinaria.</p>
            <p>5.	Comunidades: Resolución de conflictos e integración social</p>
        </div>
    </section>

    <section id="unidad3">
        <h2 onclick="toggleSubtema('subtemas3')" style="cursor:pointer;">Unidad 3: La Comunicación en el Ambito Empresarial</h2>
        <div id="subtemas3" style="display: none; margin-left: 20px;">
            <h3>3.1 Bla Bla Bla </h3>
            <p>Bla Bla Bla Bla Bla Bla</p>
            <h3>3.2 Bla Bla</h3>
            <p>Bla Bla BLA bla</p>
            <h3>3.3 Bla Bla Bla Bla Bla Bla</h3>
            <p>Bla Bla Bla Bla </p>
        </div>
    </section>

    <section id="NO TOCAR">
    <h2 onclick="toggleSubtema('Subtema4')" style="color: red;">NO TOCAR! PELIGRO </h2>
        <div id="Subtema4" style="display: none; margin-left: 20px;">
            <h3> OPCION TROLL JAJAJAJAJAJAJAJAJAJAJA 🤣 </h3>
            <img src="https://i.pinimg.com/236x/69/a2/99/69a2994bf4e91a83a0942b9468782d29.jpg" alt="Foto Troll">
        </div>
    </section>

    <footer>
        2025 Liderazgo y Gestión de Equipos
    </footer>

    <!-- JavaScript para desplegar subtemas -->
    <script>
        function toggleSubtema(id) {
            const div = document.getElementById(id);
            if (div) {
                div.style.display = div.style.display === "none" ? "block" : "none";
            }
        }
    </script>

</body>

</html>
