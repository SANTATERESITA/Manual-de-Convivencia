<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manual de Convivencia Escolar</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f6f9;
            color: #333;
        }
        nav {
            background-color: #2c3e50;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            transition: transform 0.3s ease-in-out;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            position: relative;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            padding: 15px 20px;
            display: block;
            font-size: 1rem;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: background-color 0.3s ease;
        }
        nav ul li a:hover {
            background-color: #1abc9c;
        }
        nav ul li ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #34495e;
            list-style-type: none;
            padding: 0;
            margin: 0;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        nav ul li ul li a {
            padding: 10px 20px;
            font-size: 0.9rem;
        }
        nav ul li:hover ul {
            display: block;
        }
        .breadcrumbs {
            padding: 10px 20px;
            background-color: #ecf0f1;
            font-size: 0.9rem;
            display: flex;
            gap: 5px;
            margin-top: 60px; /* Para evitar superposición con la barra */
        }
        .breadcrumbs a {
            text-decoration: none;
            color: #2c3e50;
        }
        .breadcrumbs a:hover {
            text-decoration: underline;
        }
        .breadcrumbs span {
            color: #7f8c8d;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            font-size: 2rem;
            margin: 20px;
        }
        h2 {
            font-size: 1.5rem;
            margin: 15px 20px;
        }
        h3 {
            font-size: 1.2rem;
            margin: 10px 20px;
        }
        p {
            font-size: 1rem;
            line-height: 1.6;
            margin: 10px 20px;
            color: #555;
        }

        /* Ocultar menú en dispositivos pequeños */
        @media (max-width: 768px) {
            nav ul li ul {
                position: static;
            }
            nav ul li:hover ul {
                display: none; /* Evitar que se mantenga abierto con hover en pantallas pequeñas */
            }
            nav ul li.active ul {
                display: block; /* Mostrar solo cuando esté activo */
            }
        }
    </style>
</head>
<body>
    <nav id="navbar">
        <ul>
            <li>
               <a href="#introduccion"><span>🏠</span> Presentación</a>
                <ul>
                    
                    <li><a href="#pei">contenido del Manual de Convivencia Escolar</a></li>
                    <li><a href="#comité">Comité de Convivencia Escolar</a></li>
                  </ul>
             </li>
             <li>
                <a href="#manual"><span>📖</span> Manual de Convivencia</a>
                <ul>
                    <li><a href="#manual">Introducción</a></li>
                    <li><a href="#estructura">Estructura del Manual de Convivencia Escolar</a></li>
                    <li><a href="#capitulo-I">Referentes conceptuales y legales</a></li>
                    <li><a href="#capitulo-II">Horizonte Institucional</a></li>
                    <li><a href="#capitulo-III">Metas Institucionales – Criterios</a></li>
                    <li><a href="#capitulo-IV">Actores Fundamentales</a></li>
                    <li><a href="#capitulo-V">Deberes y derechos de las Estudiantes</a></li>
                    <li><a href="#capitulo-VI">Gobierno Escolar</a></li>
                    <li><a href="#capitulo-VII">Estamentos democráticos</a></li>
                    <li><a href="#capitulo-VIII">Representantes estudiantiles</a></li>
                    <li><a href="#capitulo-IX">Obligaciones complementarias de la Institución Educativa</a></li>
                   </ul>
             </li>
             <li>
                <a href="#introduccion"><span>⚖️</span> Sistema Nacional de Convivencia Escolar</a>
                <ul>
                    <li><a href="#capitulo-X">El Papel de los Actores Sociales</a></li>
                    <li><a href="#capitulo-XI">Sistema Nacional de Convivencia Escolar</a></li>
                    <li><a href="#capitulo-XII">Clasificación de situaciones que afectan la convivencia escolar</a></li>
                    <li><a href="#capitulo-XIII">Estrategias Convivenciales</a></li>
                </ul>
            </li>
        </ul>
    </nav>
    <div class="breadcrumbs">
        <a href="#">Inicio</a> <span>></span>
        <a href="#introduccion">Presentación</a> <span>></span>
        <span>Manual de Convivencia</span>
    </div>
    <main>

    <h1 id="introduccion">Presentación</h1>
    <h2 id="introduccion-principal">“Fortaleciendo procesos hacia el mejoramiento continuo”</h2>
    
            <p>El Manual de Convivencia Escolar es un documento fundamental que establece las normas, principios y valores que rigen la convivencia dentro de la Institución Educativa Santa Teresita. Su contenido está diseñado para orientar y guiar a todos los miembros de la comunidad educativa, promoviendo un ambiente seguro, respetuoso y constructivo. Este documento detalla aspectos esenciales como la misión y visión de la institución, que representan la dirección y los objetivos formativos a largo plazo, y definen el carácter y la razón de ser del colegio. La misión y visión también son los pilares que inspiran a cada miembro a comprometerse con una educación integral y de calidad.</p>
            <p>Además, el manual incluye una declaración de los principios y valores que rigen la convivencia escolar. Estos valores, tales como el respeto, la tolerancia y la responsabilidad, no solo son conceptos abstractos, sino que se traducen en comportamientos concretos y actitudes que deben practicar todos los miembros de la comunidad educativa. Estos principios son fundamentales para construir un ambiente donde la diversidad sea valorada y donde cada persona tenga la oportunidad de crecer y desarrollarse plenamente.</p>
            <p>Otro aspecto importante que cubre el manual son los derechos y responsabilidades de estudiantes, padres de familia, docentes y personal administrativo. Establecer derechos claros ayuda a garantizar que todos los miembros de la comunidad educativa se sientan protegidos y valorados, mientras que definir responsabilidades asegura que cada uno comprenda su rol en el mantenimiento de un ambiente de aprendizaje positivo y constructivo. Al tener claridad en estos aspectos, se fomenta una cultura de responsabilidad y respeto mutuo que es esencial para la convivencia armoniosa en el entorno escolar.</p>
            <p>El manual también especifica las normas de comportamiento y el código de conducta, junto con los procedimientos para resolver conflictos y manejar situaciones críticas. Estos elementos son esenciales para mantener el orden y la seguridad en la escuela, así como para abordar de manera constructiva los conflictos que puedan surgir. El código de conducta y los procedimientos establecidos ayudan a que todos los miembros de la comunidad educativa sepan cómo actuar ante situaciones de conflicto, promoviendo una resolución pacífica y evitando que las situaciones se agraven.</p>
            <p>Finalmente, el Manual de Convivencia incluye programas y estrategias para fomentar la convivencia y prevenir la violencia, así como medidas disciplinarias y de protección para las víctimas de acoso escolar o violencia. Estas disposiciones son vitales para el desarrollo integral de los estudiantes y para crear un ambiente en el que todos puedan sentirse seguros y respetados. El manual no solo funciona como una herramienta para la prevención de conflictos, sino que también es un recurso para construir una comunidad escolar más justa y comprometida con el bienestar y el desarrollo de todos sus miembros.</p>
        </section>

        
<li><a href="#">Menú</a></li>
    </main>.</p>
</ul>
    </nav>

             </section>

    </main></p>
    <h2 id="pei">Contenido del Manual de Convivencia Institucional</h2>


     <p>Con el presente manual, buscamos promover y garantizar un ambiente de respeto, tolerancia y convivencia pacífica dentro de la institución educativa, asegurando el bienestar y el desarrollo integral de todos los miembros de la comunidad educativa.</p>
     
   

<main>
        <!-- Contenido del Manual -->
        <section id="contenido">
            
            <p>El Manual de Convivencia Escolar incluye los siguientes elementos:</p>
            <div class="content-list">
                <div class="content-item">
                    <h3>1. Misión y Visión de la Institución Educativa</h3>
                    <p>Descripción de los objetivos y metas de la institución.</p>
                </div>
                <div class="content-item">
                    <h3>2. Principios y Valores que Rigen la Convivencia Escolar</h3>
                    <p>Normas éticas y morales que fortalecen el ambiente escolar.</p>
                </div>
                <div class="content-item">
                    <h3>3. Derechos y Responsabilidades</h3>
                    <p>Los derechos y deberes de los estudiantes, padres, docentes y personal administrativo.</p>
                </div>
                <div class="content-item">
                    <h3>4. Normas de Comportamiento y Código de Conducta</h3>
                    <p>Reglas y comportamientos esperados en el ambiente escolar.</p>
                </div>
                <div class="content-item">
                    <h3>5. Procedimientos para Resolver Conflictos</h3>
                    <p>Pasos a seguir para manejar conflictos y situaciones críticas.</p>
                </div>
                <div class="content-item">
                    <h3>6. Medidas Disciplinarias y Sanciones</h3>
                    <p>Consecuencias de incumplir las normas de convivencia.</p>
                </div>
                <div class="content-item">
                    <h3>7. Programas y Estrategias para Fomentar la Convivencia</h3>
                    <p>Iniciativas para fortalecer la convivencia y prevenir la violencia.</p>
                </div>
                <div class="content-item">
                    <h3>8. Protección y Atención a Víctimas</h3>
                    <p>Protocolos de apoyo y protección para víctimas de acoso escolar o violencia.</p>
                </div>
            </div>
        </section>

        <!-- Importancia del Manual -->
        <section id="importancia">
            <h2>Importancia del Manual de Convivencia Escolar</h2>
            <p>El Manual de Convivencia Escolar es fundamental para:</p>
            <div class="importance-list">
                <div class="importance-item">
                    <h3>1. Establecer un Ambiente de Respeto y Tolerancia</h3>
                    <p>Promover el respeto mutuo y la inclusión en toda la comunidad educativa.</p>
                </div>
                <div class="importance-item">
                    <h3>2. Prevenir y Manejar Conflictos</h3>
                    <p>Facilitar la resolución de problemas y la gestión de situaciones críticas.</p>
                </div>
                <div class="importance-item">
                    <h3>3. Fomentar la Responsabilidad y el Compromiso</h3>
                    <p>Incentivar el compromiso de todos los miembros de la comunidad educativa.</p>
                </div>
                <div class="importance-item">
                    <h3>4. Garantizar el Bienestar y el Desarrollo Integral de los Estudiantes</h3>
                    <p>Asegurar un entorno seguro y saludable para el crecimiento de los estudiantes.</p>
                
<li><a href="#">Menú</a></li>

</section>

    </main></p>
    <h2 id="comité">Comité de Convivencia Escolar</h2>
    
            </section>

</ul>
    </nav>
       
       <p>El Manual de Convivencia Escolar debe ser revisado y actualizado periódicamente, con la participación de todos los miembros de la comunidad educativa, para asegurar su relevancia y efectividad. El Manual de Convivencia Escolar debe ser implementado y difundido en toda la institución educativa, asegurando que todos los miembros de la comunidad educativa lo conozcan y lo respeten.</p>
<p>En la Institución Educativa Santa Teresita, nos comprometemos a crear un ambiente de convivencia pacífica y respetuosa, donde todos los miembros de la comunidad educativa puedan crecer y desarrollarse de manera integral.</p>

<h2 id="manuales-convivencia">Resolución No. 02 - (abril 17 de 2024)</h2>

<p>“Por medio de la cual se definen los integrantes y funciones del comité de convivencia escolar para el año lectivo 2024”</p>
<p>El Rector de la Institución Educativa Santa Teresita en ejercicio de las facultades constitucionales, legales Vigentes, y numeral 12 del artículo 5 de la ley 115 de 1994, ley 1098 decreto 1860, lineamientos técnicos de 2014, y las orientaciones dadas al respecto por el MEN, en el decreto 1852, expedido 16 de septiembre de 2015 y la resolución no. 16432 del 2 de octubre de 2015, mediante la cual se expidieron los lineamientos técnicos – administrativos, los estándares, y</p>
<p>CONSIDERANDO:</p>
<p>Que la ley 115, en su artículo 87 legisla sobre el reglamento o Manual de Convivencia.</p>
<p>Que la Ley 1620 en sus artículos 12 y 13, señala los parámetros para la conformación del comité de convivencia y sus funciones.</p>
<p>Que la guía 34 de mejoramiento institucional señala la importancia de los comités de convivencia.</p>
<p>Que durante el presente año se realizó el ejercicio de actualización del Manual de convivencia de la institución,</p>
<p>Que el equipo directivo revisó y aprobó los perfiles docentes de los representantes de cada jornada</p>
<p>Que es fundamental para los procesos de convivencia escolar, la sistematización, seguimiento y análisis de los casos presentados para diseñar estrategias de mejoramiento y acompañamiento.</p>
<p>Que el Manual de Convivencia contempla conformar un comité institucional y comités de seguimiento por sede.</p>
<p>RESUELVE</p>
<p>ARTÍCULO PRIMERO:</p>
<p>De acuerdo a la normatividad vigente se crea el Comité Escolar de Convivencia como una instancia del establecimiento educativo encargada de apoyar la labor de promoción y seguimiento a la convivencia escolar, a la educación para el ejercicio de los Derechos Humanos, Sexuales y Reproductivos, así como al desarrollo del Manual de Convivencia y a la Prevención y Mitigación de la Violencia Escolar.</p>
<p>El comité de convivencia de la Institución Educativa SANTA TERESITA, el cual quedará conformado por:</p>
<p>El rector del establecimiento educativo: HUMBERTO ANTONIO CORTES QUIÑONES</p>
<p>La personera estudiantil: MELANY GABRIELA OLIVEROS SOLIS</p>
<p>La docente orientadora: DIANA SEVILLANO</p>
<p>La coordinadora que presidirá: JULIA PEREA ANGULO</p>
<p>Los coordinadores: CESAR FERNANDO CUARTAS, DAVID ARMANDO URBANDO, ANIBAL FERNEY QUIÑONES</p>
<p>Un representante de los padres de familia: Diana Campaz.</p>
<p>Dos docentes que lideren procesos o estrategias de convivencia escolar de cada sede:</p>
<p>Angie Cortes – Cristina Fernández Vélez</p>
<p>Ricardo Cruel – Rosa Batioja</p>
<p>Alba Felisa Góngora – Beiby Patricia Garcés</p>
<p>Ana Borja – Meiber Rosero</p>
<p>ARTÍCULO SEGUNDO:</p>
<p>El comité de Acompañamiento por bloque académico, se conformará con los integrantes del comité institucional que pertenecen al bloque específico, el objetivo es tratar oportunamente las situaciones de convivencia, que no requieran ser tratadas por el comité institucional y depurar los casos para que lleguen de manera correcta al comité institucional.</p>
<p>ARTÍCULO TERCERO:</p>
<p>Son funciones del comité de convivencia, las descritas en la ley 1620, tales como:</p>
<p>Identificar, documentar, analizar y resolver los conflictos que se presenten entre docentes y estudiantes, directivos y estudiantes, entre estudiantes y entre docentes.</p>
<p>Liderar en los establecimientos educativos acciones que fomenten la convivencia, la construcción de ciudadanía, el ejercicio de los derechos humanos, sexuales y reproductivos y la prevención y mitigación de la violencia escolar entre los miembros de la comunidad educativa.</p>
<p>Promover la vinculación de los establecimientos educativos a estrategias, programas y actividades de convivencia y construcción de ciudadanía que se adelanten en la región y que respondan a las necesidades de su comunidad educativa.</p>
<p>Convocar a un espacio de conciliación para la resolución de situaciones conflictivas que afecten la convivencia escolar…</p>
<p>ARTÍCULO CUARTO:</p>
<p>Los comités de convivencia por bloque académico cumplirán las mismas funciones y realizarán informe sobre los casos atendidos al comité institucional para actualizar de manera constante las estrategias implementadas en la institución para mejorar la convivencia.</p>
<p>ARTÍCULO QUINTO:</p>
<p>La convivencia es política institucional, por ello es importante recordar la responsabilidad de los docentes, como primeros orientadores en el aula, para generar ambientes propicios de respeto y convivencia, por ello se recuerdan las funciones asignadas en la ley 1620:</p>
<p>Identificar, reportar y realizar el seguimiento a los casos de acoso escolar…</p>
<p>ARTÍCULO SEXTO:</p>
<p>Son funciones del coordinador del comité de convivencia:</p>
<p>Liderar procesos de formación a la comunidad educativa que faciliten la convivencia…</p>
<p>ARTÍCULO SÉPTIMO:</p>
<p>La presente resolución rige a partir de la fecha de su expedición.</p>
<p>COMUNÍQUESE Y CÚMPLASE</p>
<p>Dada en Tumaco, a los 17 días del mes de abril de 2024</p>
<p>Rector</p>
<p>Original firmado</p>
<p></p>.</p>
<li><a href="#">Menú</a></li>


</nav>
</section>
    </main></p>


    <h1 id="manual">Introducción al Manual de Convivencia Escolar</h1>
     

<p>El Manual de Convivencia de la Institución Educativa Santa Teresita representa un pilar fundamental para el desarrollo armónico de nuestra comunidad educativa. Este documento, construido sobre la base de nuestros principios filosóficos, valores institucionales y normativas legales, establece las pautas necesarias para garantizar un entorno de respeto, inclusión y desarrollo integral.

En la IE Santa Teresita, reconocemos que la convivencia escolar es el cimiento para la formación de estudiantes autónomas, críticas y comprometidas con su entorno. Por ello, nuestro Manual de Convivencia no solo reglamenta derechos y deberes, sino que también promueve el entendimiento mutuo, la aceptación de la diversidad y la resolución pacífica de conflictos.

Este manual es una invitación a todos los miembros de nuestra comunidad—estudiantes, padres de familia, docentes y personal administrativo—a trabajar juntos por una educación que trascienda las aulas, formando mujeres líderes que contribuyan significativamente al bienestar social, cultural y económico de nuestra región.

Los lineamientos aquí establecidos están alineados con nuestro Proyecto Educativo Institucional (PEI), que busca formar mujeres integrales, con sólidos valores éticos y competencias para enfrentar los retos del siglo XXI. Invitamos a toda la comunidad a conocer, apropiarse y aplicar estas disposiciones, para que juntas construyamos un entorno escolar donde prevalezca la equidad, el respeto y la excelencia.

Bienvenidos a este espacio de construcción colectiva, donde cada norma, cada derecho y cada deber contribuyen a fortalecer la educación como un derecho, un servicio público y una herramienta transformadora.</p>

</nav>
</section>
</main></p>

<li><a href="#">Menú</a></li>

     <h1 id="estructura">Estructura del Manual de Convivencia Escolar</h1> 
            

<p>De acuerdo con la Ley General de Educación (Ley 115 de 1994) y la Ley de Convivencia Escolar (Ley 1620 de 2013), el Manual de Convivencia Escolar es un documento fundamental para cualquier institución educativa en Colombia. Este manual establece las normas y principios que regulan la convivencia dentro de la comunidad educativa.</p>
  <ul>
            
<p>Estructura</p>
<p>1. Referentes conceptuales y legales</p>
<p>2. Horizonte institucional</p>
<p>3. Gobierno escolar</p>
<p>4. Horarios de clases</p>
<p>5. El papel de los actores sociales en la gestión pedagógica del grupo</p>
<p>6. Sistema nacional de convivencia escolar y formación para el ejercicio de los derechos humanos, la educación para la sexualidad y la prevención y mitigación de la violencia escolar</p>
<p>7. Plan de acción inclusivo para población con necesidades educativas especiales (NEE)</p>
<p>8. Protocolos</p>
<p>9. Anexos</p>

<li><a href="#">Menú</a></li>
</ul>
     <h1 id="capitulo-I">Referentes conceptuales y legales</h1> 

<p>CAPITULO I</p>

<p>El Manual de Convivencia de la Institución Educativa Santa Teresita, es el conjunto de normas que regulan la vida institucional y divulga los principios filosóficos, los valores institucionales, los derechos, los deberes y funciones, la tipificación de las faltas, los estímulos, el debido proceso y los criterios de evaluación y promoción.</p>
<p>Este manual es un medio que establece los referentes que deben tener en cuenta, todos los miembros de la comunidad educativa en los diferentes procesos que allí se realizan. Se pretende que se conozca, se divulgue y se aplique para garantizar la convivencia, el respeto a la diversidad, a la inclusión, y al pensamiento divergente.</p>
<p>La Institución Educativa Santa Teresita es una institución de carácter oficial ubicada en la zona urbana del municipio de San Andrés de Tumaco, Aprobada por Resolución 4075 del 27 de diciembre de 2002, modificada mediante Resolución 248 de abril 07 de 2009, DANE 352835001605; Nit. 840.001.058-9; Ofrece los Niveles de Educación Preescolar, Básica y Media Académica, diurnas.</p>
<p>El Manual de Convivencia es un documento legal que orienta y regula la ejecución del derecho a la educación establecida en la Constitución Nacional, que conlleve a establecer pautas que regulen el ejercicio de la libertad, los deberes y los derechos de las estudiantes, padres de familia o acudientes, quienes al “firmar la matricula correspondiente en representación de sus hijas estarán aceptando el mismo” (Art.87 Ley 115/94).</p>
<p>Desarrolla y basa su accionar en las siguientes normas:</p>
<p>1. La Constitución Política de Colombia de 1991, en sus artículos:1, 2, 5, 13, 14, 16, 18, 20, 21, 22, 23, 27, 28, 40, 41, 43, 44, 45, 52, 67, 68, 73, 79, 86, 95. Especialmente los siguientes artículos:</p>
<p>• Artículo 44:” Los Derechos de los niños prevalecen sobre los derechos de los demás.</p>
<p>• Artículo 45: “El adolescente tiene derecho a la protección y a la formación integral”.</p>
<p>• Artículo 67: “La educación es un derecho de la persona y es un servicio público”</p>
<p>2. Ley de Infancia y Adolescencia. (Ley 1098 de noviembre de 2006), en sus artículos 1, 2, 3, 5, 6, 7, 8, 9, 10, 11, 18, 26, 28, 29, 30, 31, 32, 33, 36, 37, 41, 42, 43, 44, 45. Especialmente los siguientes artículos:</p>
<p>• Artículo 28: “Derecho a la educación: Los niños, las niñas y los adolescentes tienen derecho a una educación de calidad. Esta será obligatoria por el estado en un año de preescolar y nueve de educación básica…”</p>
<p>• Artículo 36: “Derechos de los niños, las niñas y los adolescentes en situación de discapacidad: Además de los derechos consagrados en la Constitución Política y en los tratados y convenios internacionales, los niños, las niñas y los adolescentes con discapacidad tienen derecho a gozar de una calidad de vida plena, y a que se les proporcionen las condiciones necesarias por parte del Estado para que puedan valerse por sí mismos, e integrarse a la sociedad…”.</p>
<p>• Artículo 42: “Obligaciones especiales de la Institución para cumplir con su misión. Las Instituciones educativas tendrán entre otras las siguientes obligaciones: Facilitar el acceso de los niños, niñas y adolescentes al sistema educativo y garantizar su permanencia y Brindar una educación pertinente y de calidad……</p>
<p>• Artículo 45: “Prohibición de sanciones crueles, humillantes o degradantes: Los directores y educadores de los centros públicos o privados de la educación formal, no formal e informal no podrán imponer sanciones que conlleve maltrato físico o psicológico de las estudiantes a su cargo, o adoptar medidas que de alguna manera afecten su dignidad. Así mismo queda prohibido su inclusión bajo cualquier modalidad en los manuales de convivencia.</p>
<p>3. La Ley General 115 de 1994, en especial los artículos 73 y 87 que obligan a todo plantel a tener un Manual de Convivencia como parte integral del Proyecto Educativo Institucional (PEI).</p>
<p>4. Ley 1620 del 15 de marzo de 2013 por la cual se crea el sistema nacional de convivencia escolar y formación para el ejercicio de los derechos humanos, la educación para la sexualidad y la prevención y mitigación de la violencia escolar.</p>
<p>5. Decreto 1965 del 11 de septiembre de 2013 "Por el cual se reglamenta la Ley 1620 de 2013, que crea el Sistema Nacional de Convivencia Escolar y Formación para el Ejercicio de los Derechos Humanos, la Educación para la Sexualidad y la Prevención y Mitigación de la Violencia Escolar."</p>
<p>6. Decreto Nacional 1860 de 1994 que establece los criterios y elementos del Manual de Convivencia y los Órganos del Gobierno Escolar, artículo 17 entre otros.</p>
<p>7. Decreto 1108 de 1994, porte de estupefacientes.</p>
<p>8. Decreto 2082 del 18 de noviembre de 1996 en el cual se reglamenta la atención en educación para las personas con limitaciones o con capacidades y talentos excepcionales.</p>
<p>9. Decreto 2247 de 1997, se establecen normas relativas a la prestación del servicio educativo del nivel preescolar.</p>
<p>10. Decreto 2694 de 1998, de las funciones del personal administrativo y personal auxiliar.</p>
<p>11. Decreto 2562 de 2001 por el cual se reglamenta la ley 387 de 1997 en cuanto a la prestación del servicio educativo a la población desplazada.</p>
<p>12. Ley 734 del 5 de febrero de 2002 por el cual se establece el código disciplinario único de servidores públicos.</p>
<p>13. Decreto 1290 del 6 de abril de 2009 en lo referente al proceso de evaluación y promoción.</p>
<p>14. Guía 49 de la serie guías pedagógicas para la convivencia escolar con base en la Ley 1620 de 2013 y el Decreto 1965 de 2013</p>
<p>15. Ley 1278 de 2002, Estatuto de Profesionalización Docente.</p>
<p>16. Decreto 1850 de 2002 Jornada Escolar y Jornada Laboral.</p>
<p>17. Sentencia SU 641 de noviembre 5 de 1998, sobre Manual de Convivencia.</p>
<p>18. Decreto 1268 del 27 de abril de 2005 en el cual se reglamentan derechos y deberes de los padres de familia.</p>
<p>19. Ley 1801 de julio 29 de 2016 por la cual se expide el Código Nacional de Policía y Convivencia. .</p>
<p></p>

<li><a href="#">Menú</a></li>

     <h1 id="capitulo-II">Horizonte Institucional</h1> 


<p>CAPITULO II</p>
<ul>

<p><h1>Visión:</h1></p>
<p>Hacia el año dos mil veintiséis, la Institución Educativa Santa Teresita de San Andrés de Tumaco será: “Centro público femenino, líder en educación y formación integral al servicio de la comunidad tumaqueña, en los niveles Preescolar, Básica y Media de educación formal, con incidencia en investigación para el desarrollo de competencias y fomento de valores convivenciales, como: respeto, responsabilidad, solidaridad, sentido de pertenencia, tolerancia y reconocimiento a la diversidad étnico - cultural y religiosa, como propuesta pertinente a los retos y exigencias de la sociedad actual, transformadora de la persona y de su entorno”.</p>

<p><h1>Misión:</h1></p>
<p>La IE Santa Teresita, centra sus esfuerzos en:</p>
<p>• Formar una persona con valores y principios en todas sus dimensiones, que se posesione de manera autónoma y pertinente en el mundo en que se desenvuelve, competente en el Saber y el Hacer con eficacia y eficiencia, que resuelva sus propios problemas y aporte soluciones a los del entorno, en forma solidaria, creativa, recursiva y competitiva; generando respuestas y opciones de cambio, en un mundo que cada día exige más.</p>
<p>• Desarrollar las potencialidades espirituales, científicas, investigativas, humanas, artísticas, lúdicas, recreativas y de promoción de la comunidad que permitan una vivencia de la libertad con responsabilidad y en proyección a la comunidad.</p>

<p><h1>Meta:</h1></p>
<p>Al finalizar el grado once, el 100% de nuestras estudiantes tendrá claridad en su proyecto de vida, el cual se verá reflejado en su compromiso al accionar, siendo competente y competitiva en el entorno en que se desempeña.</p>

<p><p><h1>Objetivo Estratégico:</h1></p>
<p>La institución busca formar mujeres que se transformen para enfrentar con objetividad y responsabilidad los retos y desafíos que impone la sociedad actual, que vivencien valores espirituales, morales, intelectuales, culturales, sociales, democráticos, investigativos y participativos, que sean líderes, artífices de su propio destino, comprometidas en la transformación de su comunidad.</p>

<p>Valores de Formación:</p>
<p>En la Institución Educativa Santa Teresita, se dirigen los esfuerzos a formar principalmente en los siguientes valores, con sus correspondientes actitudes, que han sido evaluados y adoptados en consenso, con toda la comunidad educativa:</p>
<p>RESPETO: Concebido como un valor que permite que el hombre pueda reconocer, aceptar, apreciar y valorar las cualidades del prójimo y sus derechos. Es decir, el respeto es el reconocimiento del valor propio y de los derechos de los individuos y de la sociedad, especialmente por la vida en todas sus manifestaciones, en la convivencia y trato con los demás y consigo mismo.</p>
<p>RESPONSABILIDAD: La responsabilidad, se asume como un valor que está en la conciencia de la persona, que le permite reflexionar, administrar, orientar y valorar las consecuencias de sus actos, en el plano de lo moral y de lo ético.</p>
<p>Por lo tanto, la persona responsable en esta institución, es aquella que actúa conscientemente, siendo la causa directa o indirecta de un hecho ocurrido y está obligada a responder por sus actos, sus deberes y sus derechos y en todos los procesos y compromisos adquiridos con la Comunidad Educativa.</p>
<p>SOLIDARIDAD: Es un valor que nos permite dar con generosidad, todo aquello que de Dios hemos recibido. En la IE Santa Teresita, es asumida como la capacidad de entregarse a otros como sus semejantes; es decir, poder compartir con ellos, en lo material y espiritual lo que se posee, independientemente de la situación de ambos. En sí, se trata de ayudar a la comunidad con los bienes, servicios o respuestas a tiempo, ofreciendo apoyo incondicional al que lo necesite.</p>
<p>SENTIDO DE PERTENENCIA: Entendido como el sentimiento de sentirse parte de la institución, siendo fiel, siguiendo las normas de convivencia que le da una identidad y una seguridad, mientras más segura se sienta la persona, más elevado será su sentimiento comunitario, con los diferentes miembros de la comunidad educativa y estará más dispuesta a seguir normas de convivencia. En este sentido, se trata de manifestar pertenencia a sus bienes, a los de la institución, con el medio ambiente y con el grupo de pares a que pertenece.</p>
<p>Algunas de las normas que la persona debe seguir cuando pertenece a la institución o a un grupo, son:</p>
<p>Participar activamente en los procesos de la institución o grupo</p>
<p>Asumir con responsabilidad los compromisos que adquiere al ingresar.</p>
<p>Respetar a todos los miembros de la institución o del grupo</p>
<p>Respetar la filosofía, las políticas y normas de la Institución.</p>
<p>Respetar los símbolos de la Institución: uniformes, bandera, escudo, etc.</p>
<p>Actuar teniendo en cuenta las normas que contribuyen a la convivencia en su institución.</p>
<p>Querer, valorar y reconocer la importancia de la institución en la sociedad.</p>
<p>No afectar a la institución, ni a sus pertenencias, de ninguna manera.</p>
<p>TOLERANCIA: La tolerancia es uno de los valores humanos más respetados y guarda relación con la aceptación de aquellas personas, situaciones o cosas que se alejan de lo que cada persona posee o considera dentro de sus creencias. La tolerancia es posible de medir en determinados grados que guardan relación con la aceptación que se tenga ante algo con lo que no se está de acuerdo o que no se adecua al propio sistema de valores.</p>
<p>La importancia de la tolerancia radica en la posibilidad que nos otorga de convivir en un mismo espacio con personas de diferentes culturas o con diferentes creencias. La tolerancia es la que nos permite vivir en armonía en un mismo país con personas que profesan diferentes religiones, que apoyan otras tendencias políticas, que poseen una condición sexual diferente, etc. La tolerancia no sólo es aplicable a nivel de país, sino que es algo que debemos desarrollar en nuestra institución, los hogares, con aquellas personas a las que más queremos, como nuestra familia y amigos, así como también, a nivel mundial, donde se intenta convivir en armonía con un sinnúmero de culturas y personas muy diversas.</p>
<p>Como vemos, la tolerancia se encuentra en estrecha relación con el respeto, pudiendo así ser capaces de aceptar las diferentes opiniones en torno a un mismo tema, aceptando y respetando las diferencias étnicas, sociales, culturales y religiosas, entre otras, teniendo siempre en cuenta que aquello que estemos respetando no atente contra la integridad y los derechos de las personas, animales y el medio ambiente.</p>
<p>HONESTIDAD: La honestidad es una cualidad humana que consiste en comportarse y expresarse con coherencia y sinceridad, y de acuerdo con los valores de verdad y justicia. En su sentido más evidente, la honestidad se entiende en la IE Santa Teresita, como el simple respeto a la verdad en relación con el mundo, los hechos y las personas; en otros sentidos, la honestidad también implica la relación entre el sujeto y los demás, y del sujeto consigo mismo.</p>
<p>Dado que las intenciones se relacionan estrechamente con la justicia y se relacionan con los conceptos de "honestidad" y "deshonestidad", existe una confusión muy extendida acerca del verdadero sentido del término. Así, no siempre somos conscientes del grado de honestidad o deshonestidad de nuestros actos: el auto-engaño hace que perdamos la perspectiva con respecto a la honestidad de los propios actos, obviando todas aquellas visiones que pudieran alterar nuestra decisión.</p>
<p>De manera interdisciplinaria, la IE también se esfuerza por formar actitudes y valores, espirituales, personales, sociales y económicos, tales como:</p>
<p>ESPIRITUALES: De gran espiritualidad, trascendencia moral y ética, amor por sí misma, por la institución, por los otros. El amor, como valor que orienta la vida institucional, humaniza y consolida la armonía entre los miembros de la I.E., fe y creencia en un Ser Supremo.</p>
<p>PERSONALES: Autonomía, amistad, entusiasmo, compromiso, autoestima, libertad, desarrollo de la competitividad, seguridad en sí misma, lealtad, generosidad, conciencia de su ser y estar en este mundo, sentido crítico, compromiso individual y colectivo con su proyecto de vida, reconocimiento del valor propio y de los derechos de los demás, la afectividad como amor hacia los demás, la gratitud, el amor y el cariño.</p>
<p>SOCIALES: Respeto y cuidado por el medio ambiente y por los animales, cuidado de los bienes públicos y de la institución, promoviendo una cultura de convivencia y reconciliación. Actitudes como la cooperación y la solidaridad con los demás, entendiendo que la vida es un regalo de Dios y que todos tienen derecho a vivir en paz y armonía.</p>
<p>ECONÓMICOS: Cuidado en el uso de recursos, el respeto por el trabajo y el esfuerzo de los demás, el desarrollo del sentido del deber, el cumplimiento de los compromisos establecidos, como el pago a tiempo de las cuotas de matrícula.</p>

<p><h1>Filosofía:</h1>.</p>
<p>La Institución Educativa Santa Teresita de San Andrés de Tumaco, basa su filosofía en la formación integral de la persona, desde el compromiso social y de servicio a la comunidad, en la vivencia de los valores, en todos los espacios y eventos de la vida diaria. Apunta a la formación en la diversidad, basándose en principios como: el respeto a la persona, considerándolo como un legítimo otro, desde la diferencia y la convivencia; a la vida y a la libertad, que le permitan a la estudiante ser capaz de enfrentarse a situaciones difíciles, y a su vez contribuir al crecimiento de su entorno familiar y social.</p>
<p>Consecuente con lo anterior, la IE Santa Teresita fundamenta su filosofía, teniendo en cuenta los valores personales, institucionales, espirituales, sociales y económicos para hacer de la estudiante teresiana un ser trascendente, que sea útil a su familia y a la sociedad.</p>
<p>Principios y Fundamentos que Nos Orientan:</p>
<p>- De trascendencia, que permita promover el desarrollo de la dimensión espiritual.</p>
<p>- De autonomía, liderazgo y visión de futuro para construir un mundo digno, justo y humano.</p>
<p>- De equidad, inclusión y diversidad, que fomenten el respeto a la diferencia, interculturalidad y la pluriculturalidad, el sentido de pertenencia y convivencia pacífica.</p>
<p>- De identidad, que permita desarrollarse y valorarse como ser social y étnico.</p>
<p>- De conocimiento y amor a la ciencia e investigación, fomentar herramientas intelectuales y sociales que permiten un aprendizaje reflexivo y continuo.</p>
<p>- De mentalidad emprendedora, para desarrollarse laboral y productivamente.</p>

<p><h1>Principios y Fundamentos:</h1>.</p>

Los principios y fundamentos para nuestra institución educativa son fundamentales por las siguientes razones:
<p>1.	Identidad institucional: Reflejan la esencia y valores fundamentales que guían la educación en el colegio. Ayudan a nuestras estudiantes, padres de familia y comunidad a entender la misión y visión de la institución..</p>
<p>2.	Fortalecimiento del proyecto educativo: Subrayan el enfoque Socio Histórico Cultural, que distingue a Santa Teresita de otras instituciones.</p>
<p>3.	Transparencia y confianza: Permite que la comunidad educativa tenga claridad sobre los valores que se inculcan, lo que genera confianza y fortalece la relación con padres y estudiantes..</p>
<p>4.	Promoción de la convivencia: Promueven normas de comportamiento y actitudes que garantizan un ambiente armonioso y respetuoso, especialmente relevante en una institución de carácter femenino como la nuestra..</p>
<p>5.	Inspiración y motivación: Actúan en nuestras estudiantes como una guía para formar su carácter y proyectarse como mujeres líderes, éticas y comprometidas con la sociedad..</p>
<p> En resumen, los principios para el Colegio Santa Teresita no solo reafirman nuestra identidad y propósito, sino que también comunica de manera efectiva los valores que ofrece a la comunidad, fortaleciendo su imagen institucional..</p>
<ul>
<p><h1>Principios Antropológicos:</h1>.</p>
<p>La IE Santa Teresita centra sus esfuerzos en la formación humana integral de mujeres, con las siguientes características:</p>
<p>• Con alta autoestima, liderazgo, autónoma, creativa, investigativa, solidaria, capaz de desenvolverse en una sociedad multicultural.</p>
<p>• Con identidad étnica, defensora de su territorialidad, que se eduque con principios y valores propios de su cultura, respetando los saberes populares y costumbres de la tradición oral, en vivencia de su espiritualidad.</p>
<p>• Que transforme su mentalidad viviendo la libertad física, política, religiosa y ética.</p>
<p>• Que luche por el respeto y reconocimiento de los derechos humanos.</p>
<p>• Con conciencia clara, cuando participe en la toma de las decisiones que la afectan.</p>
<p>• Conocedora de su realidad y capaz de interpretar el mundo moderno desde sus tradiciones.</p>
<p>• Investigadora de su cultura.</p>
<p>• Que contribuya a la formación de personas con capacidad de liderazgo para el bien común.</p>
<p>• Persona apta para el trabajo digno.</p>

<p><h1>Principios Axiológicos:</h1></p>
<p>• Para facilitar el proceso pedagógico y hacer énfasis en la convivencia en valores es necesario plantear la conceptualización de hombre - mujer por formar, como un ser integral, desde sus dimensiones: espiritual, afectiva, psicológica, biológica y social, retomando tres elementos indispensables: valores, actitud y motivación.</p>
<p>• La razón de ser de la institución es la formación de una mujer enriquecida espiritualmente, con sólidos principios y valores éticos, morales y de respeto por las diferencias individuales, creencias y cultos.</p>
<p>• Los valores hacen referencia a la formación de la estudiante frente al ser - saber – hacer y actuar dentro de un contexto determinado, sin importar sus dificultades intelectuales o de otro tipo.</p>
<p>• Los valores como principios fundamentales del comportamiento humano pueden motivar el Ser y el Querer Ser de las personas generando una visión del mundo y una actitud positiva ante la vida, optimista e innovadora.</p>
<p>• Que demuestre seguridad, confianza y deseo de superación en lo que hace. Para lograr esto se debe comenzar por afectar en forma positiva las representaciones internas que va haciendo la niña o adolescente de su realidad, aún en las peores circunstancias en que puede vivir. Es pues, un reto para los docentes de esta institución formar personas con actitudes coherentes, amantes de la vida, con ideas, sentimientos y propuestas que dignifiquen a la PERSONA O SER HUMANO.</p>
<p>• Conocedoras de su cultura, desde donde puede multiplicar el evangelio, dando testimonio de vida.</p>
<p>• Formación de la mujer en su dimensión intelectual, afectiva, espiritual, con sentido de pertenencia que sepa proyectarse y ser protagonista de cambios sociales.</p>

<p><h1>Principios Epistemológicos:</h1></p>
<p>El conocimiento es concebido como un acto social, en la medida que la estudiante interactúa dentro de un contexto social. En los primeros años de vida de la niña, integra la información de manera rudimentaria estableciendo relaciones más de tipo circunstancial que lógico, apareciendo las nociones en la medida en que el proceso biológico va haciéndose más complejo, de esta manera, el nivel de integración de la nueva con la antigua información es más especializada. Así, el individuo construye conceptos para finalmente llegar a las categorías.</p>
<p>Es a través de este proceso que Piaget plantea que la persona construye conocimiento. De ahí la importancia de la actividad del sujeto que aprende en el proceso de conocimiento. Este actuar se conoce como “de las formas”, primero las acciones que tiene el individuo al interactuar con el medio que lo rodea y segundo, el actuar mental que realiza el individuo para apropiarse y construir conocimientos. Estos dos procesos fundamentales en su teoría son: la asimilación y la acomodación. El aprendizaje de conceptos incluiría a su vez, dos tipos: la formación de conceptos a partir de experiencias empíricas concretas, es decir, a partir de los objetos. Dicho aprendizaje, estaría basado en situaciones de descubrimiento e incluiría procesos como la diferenciación, la generalización, la formulación y la comprobación de hipótesis. Y en segundo lugar, la adquisición de conceptos a partir de los ya preexistentes, en donde el estudiante, a medida que recibe la información, va relacionando los nuevos conceptos con los anteriormente formados.</p>

<p>A estos procesos se unen las condiciones personales de tipo biológico, genético, en donde el individuo internaliza la información que capta del medio y debe integrarla, acomodarla con la información que ya tiene, que ha construido. Cuantas más relaciones establezca entre los conocimientos que ya posee y la nueva información, el aprendizaje es más complejo. Y las condiciones de tipo social, por eso, se busca propiciar un enfoque pedagógico interestructurante y contextual, el cual está relacionado con las múltiples posibilidades de interacción que tiene el estudiante, tales como: persona - grupo y persona – grupo - medio.</p>
<p>Los procesos del Aprendizaje Significativo Constructivo sirven de base para el perfeccionamiento y la formación de sujetos con una visión de transformación y desarrollo científico y tecnológico. De esta manera, se hace posible el aprovechamiento de las capacidades tanto de estudiantes como de docentes, en la organización y construcción de nuevos conceptos, procesos académicos y tecnológicos, logrando así, el planteamiento de acertados desarrollos conceptuales y de innovaciones tecnológicas.</p>
<p>Los anteriores principios son complementados con el principio psicológico, según el cual es necesario comprender que los factores de un contexto particular (socioeconómico, cultural, geográfico, comunicativo, discursivo, ideológico, simbólico y biológico) influyen de manera independiente y conjunta en la forma como un individuo y una comunidad específica desarrollan su modo de entender, manejar y modificar el medio en que vive. Por lo tanto, el conocimiento que el individuo construye tiene sentido solamente dentro de un contexto específico y concreto.</p>

<p><h1>Principios Pedagógicos:</h1><p>
<p>El conocimiento es inseparable de la acción misma; de esta manera se habla de conocimientos y procedimientos que involucran el SABER con el HACER. Este hacer implica una relación estrecha e íntima con el contexto donde se desarrollan los procesos pedagógicos, abordando problemas reales y obteniendo resultados importantes para la persona involucrada en el aprendizaje. Por eso, en la IE Santa Teresita, se busca la formación de una persona investigadora, que tenga gusto por descubrir y construir conocimiento, interés por encontrar una explicación y un entendimiento de la realidad, que además de gustarle lo que aprende, lo use en cualquier ámbito y contexto.</p>
<p>El modelo pedagógico es el (socio-histórico-cultural) que asume enfoques pedagógicos interestructurantes que responden a los desafíos y demandas que la sociedad realiza a la educación, permitiendo plantear propuestas educativas innovadoras en coherencia con los planteamientos del Proyecto Educativo Institucional. Por tanto, la pedagogía se concibe como una disciplina educativa desde la cual se elaboran las vías culturales y axiológicas que dan sustento al perfeccionamiento de la sociedad desde sus propias demandas e inquietudes.</p>
<p>La enseñanza es la forma indispensable de generar el desarrollo mental de las estudiantes. Este enfoque afirma que el niño reconstruye los conocimientos ya elaborados por la ciencia y la cultura, siendo el lenguaje un mediador. Su aporte psicológico es la teoría de la Zona de Desarrollo Próximo, la cual sostiene que el aprendizaje y el desarrollo son interdependientes.</p>
<p>Retoma el rol protagónico de la estudiante como el sujeto de sus procesos de aprendizaje, rescata al docente de la marginalidad y lo ubica como sujeto de los procesos de enseñanza. Considera el conocimiento como el legado cultural de la humanidad, digno de ser conocido y comprendido. Considera la comprensión de la realidad como el punto de llegada, para cuyo estudio confluyen diferentes procesos cognitivos adquiridos con anterioridad. Se centra en el individuo como realidad sociocultural.</p>


<p><h1>Fundamentos Sociológicos:</h1><p>
<p>La propuesta educativa de la Institución Educativa Santa Teresita concibe la formación en, y para, una sociedad centrada en los siguientes criterios. Una sociedad que propenda por la formación de estudiantes con altas calidades tanto académicas como humanas.</p>
<p>Con unidad, ética familiar y respeto a los demás, que propenda por el fortalecimiento de los grupos étnicos.</p>
<p>Que busque el desarrollo intelectual para conocer lo propio y lo de los demás.</p>
<p>Solidaria, sensible, que busque recuperar las culturas y valores ancestrales.</p>
<p>Que desarrolle el sentido del ahorro y la buena administración, solidaria, colectiva y humana.</p>
<p>Liberadora, con sentido de pertenencia al territorio, en relación armónica con el medio ambiente.</p>
<p>Que defienda el trabajo colectivo, que forme con visión ancestral, igualdad social y cooperación.</p>
<p>Conocedora de su historia, que cuide sus patrimonios y respete lo que hay dentro de su entorno.</p>
<p>Que interactúe con otras comunidades sin racismo, con igualdad de oportunidades.</p>
<p>Autónoma y respetuosa de las autoridades.</p>
<p>Que reconozca a la familia como la base de la comunidad.</p>
<p>Que participe del conocimiento de la historia de la comunidad.</p>
<p>Que manifieste respeto por la vida, por la etnicidad y la territorialidad.</p>
<p>Democrática, abierta al mundo, capaz de resolver sus propios problemas.</p>
<p>Capaz de aprovechar las potencialidades de nuestro entorno.</p>
<p>Con poder político y étnico, gestora de su propio desarrollo a partir de su ancestralidad.</p>
<p>Que recupera su sentido colectivo, siendo solidaria, que conviva en armonía y genere soluciones pacíficas a los conflictos.</p>
<p>Conocedora de su propia cultura y del mundo globalizado, buscando las mejores formas de insertarse en ella de manera activa y productiva.</p>
<p>Formadora de líderes capaces de transformar la realidad, al elegir con conciencia a sus representantes.</p>
<p>De seres comprometidos, líderes responsables con principios y valores dispuestos a ser y creer como personas exitosas.</p>

<p><h1>Fundamentos Epistemológicos:</h1><p>
<p>Trabajar en la construcción de los saberes, a través de:</p>
<p>Mejorar el hábito de lectura y escritura en lo personal y comunitario.</p>
<p>Fortalecer el diálogo de saberes en el concepto de la universalidad (interculturalidad).</p>
<p>Conocer la diáspora africana y los saberes ancestrales.</p>
<p>Aportar a la construcción de una espiritualidad propia.</p>
<p>Conocer las prácticas y medicina tradicionales, con conocimientos históricos.</p>
<p>Tecnología de alimentación, en el agua y en los recursos como el manglar y su biodiversidad.</p>
<p>Apuntar al desarrollo industrial, ecoturístico y biodiverso de la región.</p>
<p>Conocer sus derechos como pueblo étnico negro.</p>
</ul>
<li><a href="#">Menú</a></li>

     <h1 id="capitulo-III">Metas Institucionales – Criterios</h1> 

<p>CAPITULO III</p>
<ul>
<p>• En el 2019, se inicia un proceso de fundamentación conceptual en el Modelo Pedagógico, Socio-Histórico-Cultural, (SHC) acorde con el PEI.</p>
<p>• En el primer semestre de 2019, se realizará la reestructuración del Plan de estudios de acuerdo al Modelo Pedagógico SHC.</p>
<p>• Se fortalecerá el trabajo en equipo entre compañeros que laboran en el mismo nivel y grado. Por tal razón se hará reunión por períodos, para hacer evaluaciones de las estudiantes y, dependiendo del desempeño alcanzado, se diseñarán estrategias de acompañamiento para superación de dificultades.</p>
<p>• Durante el primer semestre de 2019, se tendrá organizado el Manual de Convivencia, y será socializado a padres de familia, docentes y estudiantes.</p>
<p>• Durante el primer semestre del año 2019 se diseñará y se pondrá en ejecución el macro proyecto investigativo institucional que será nutrido con los sub-proyectos de las áreas.</p>
<p>• Desde 2020, se implementa el Modelo Pedagógico Socio-Histórico-Cultural (SHC), fundamentado en el PEI.</p>
<p>• completar la implementación del Plan de Estudios basado en el Modelo SHC, asegurando una educación integral y de calidad.</p>
<p>• Fortalecer el trabajo en equipo mediante reuniones periódicas para evaluar y diseñar estrategias de acompañamiento para las estudiantes.</p>
<p>• Actualizar el Manual de Convivencia con la participación activa de la comunidad educativa.</p>
</ul>
<p><h1>Metas de Resultados</h1></p>
<ul>
<p>• Elevar los resultados en las pruebas SABER 11 para.</p>
<p>• Implementar proyectos investigativos y pedagógicos en todas las áreas, funcionando durante el año escolar.</p>
<p>• Elementos para Política de Inclusión</p>
<p>• La política de inclusión prioriza la atención a poblaciones vulnerables y estudiantes con discapacidad, transformando la cultura institucional para brindar atención pertinente. Esto incluye:</p>
<p>• Diagnosticar a las poblaciones vulnerables con el apoyo de equipos interdisciplinarios.</p>
<p>• Capacitar a docentes y padres de familia para atender a estas poblaciones.</p>
<p>• Diseñar estrategias pedagógicas que atiendan las Necesidades Educativas Especiales (NEE).</p>
<p>• Adaptar prácticas pedagógicas a los diferentes ritmos de aprendizaje.</p>
<p>• Promover valores de respeto, convivencia sana e inclusión en toda la comunidad educativa.</p>
<p>• Tareas Prioritarias y Permanentes</p>
<p>• Teniendo en cuenta lo anterior, son tareas prioritarias y de permanente actualización en la IE Santa Teresita:</p>
<p>• Diagnosticar la población con vulnerabilidad en situaciones físicas, intelectuales, emocionales, con ayuda de un equipo interdisciplinario de profesionales en cada campo.</p>
<p>• Capacitar tanto a docentes como a padres de familia para atender a esta población.</p>
<p>• Establecer políticas claras en cuanto a la promoción de las estudiantes, revisando este aspecto en el SIE, conforme a la nueva normatividad.</p>
<p>• Elaborar el Diagnóstico de NEE (Necesidades Educativas Especiales) de las estudiantes.</p>
<p>• Diseñar estrategias para dar trato diferenciado a la población con NEE.</p>
<p>• Solicitar asesoría a entidades gubernamentales para un mejor acompañamiento a las estudiantes con NEE.</p>
<p>• Realizar convenios con instituciones que apoyen con talento humano especializado (psicología, psiquiatría y medicina) para estudiantes con capacidades asertivas que favorezcan el buen trato e integración.</p>
<p>• Proponer actividades curriculares y extracurriculares que incluyan la participación de niñas y jóvenes en riesgo social y situación de vulnerabilidad.</p>
<p>• Capacitar a docentes en el manejo y ayudas para el aprendizaje de estudiantes con dificultades y necesidades especiales, ampliando la cobertura de la institución.</p>
<p>• Promover una política para la convivencia sana, justa y de fraternidad, acogiendo a estudiantes de diferentes medios, razas, religiones y costumbres.</p>
<p>• Implementar la Escuela de Padres para talleres que permitan conocer la realidad de las niñas y crear soluciones a las problemáticas que enfrentan.</p>
<p>• Realizar jornadas culturales para evaluar talentos, habilidades y destrezas, ayudando a formar su historia cultural y su identidad étnica.</p>
<p>• Realizar un diagnóstico para determinar cuántas estudiantes con capacidades excepcionales y NEE existen, con el apoyo de un equipo psicosocial competente.</p>
<p>• Solicitar la vinculación de profesionales como fonoaudiólogos, trabajadores sociales y psicólogos especializados en población vulnerable.</p>
<p>• Desarrollar proyectos productivos que potencien habilidades de las estudiantes para el beneficio propio y de sus familias.</p>
<p>• Proporcionar eventos de integración con diferentes actividades institucionales, destacando valores artísticos, culturales y deportivos.</p>
<p>• Plantear estrategias para mejorar la infraestructura física de la institución, atendiendo las necesidades de estudiantes con discapacidad física.</p>
<p>• Gestionar servicios de enfermería y primeros auxilios para las estudiantes.</p>
<p>• Capacitar a docentes en diversos aspectos pedagógicos para ajustar currículos a las necesidades de estudiantes con NEE.</p>
<p>• Adaptar prácticas pedagógicas según el ritmo de aprendizaje y edad biológica de las estudiantes.</p>
<p>• Buscar apoyo con instituciones para trabajar con estudiantes con alto y bajo rendimiento.</p>
<p>• Diseñar estrategias que brinden a las niñas con NEE oportunidades de superación y proyección comunitaria, erradicando la discriminación.</p>
<p>• Gestionar proyectos pedagógicos para grupos con procesos avanzados y lentos.</p>
<p>• Dar oportunidades de avance a estudiantes con procesos avanzados mediante estrategias adecuadas que les permitan alcanzar sus metas.</p>
<p>• Incluir a padres de estudiantes con capacidades especiales en actividades programadas por la institución.</p>
<p>• Desarrollar actividades especiales para estudiantes con capacidades especiales que les permitan desarrollar competencias básicas.</p>
<p>• Reajustar el PEI y el PMI para incluir a población vulnerable, sensibilizando a la comunidad sobre su presencia y necesidades.</p>
<p>• Elaborar planes de área y aula que consideren la individualidad de estudiantes con NEE.</p>
<p>• Tratar con equidad y justicia, valorando y apreciando el desempeño y comportamiento de las estudiantes.</p>
<p>• Tareas para la Inclusión Educativa</p>
<p>• Tratar con equidad y facilitar el acceso a la institución mediante adaptaciones locativas adecuadas.</p>
<p>• Buscar apoyo de presupuestos particulares a través de convenios institucionales con ONG´s que ofrezcan oportunidades para todas.</p>
<p>• Realizar un diagnóstico pormenorizado de las problemáticas, canalizando y priorizando la atención para un tratamiento adecuado.</p>
<p>• Garantizar el bienestar de la población vulnerable por NEE con profesionales éticos y de buenos valores que faciliten la expresión de ideas y pensamientos.</p>
<p>• Crear un equipo de psicoorientación con la participación de varios profesionales para una mejor atención.</p>
<p>• Establecer convenios con entidades como el SENA para ampliar el conocimiento acerca del SER y HACER de las estudiantes.</p>
<p>• Proporcionar espacios de participación para que las estudiantes con NEE puedan expresar libremente sus ideas, sin discriminación.</p>
<p>• Implementar metodologías diferenciadas para cada niña con necesidades especiales, evitando cualquier tipo de discriminación.</p>
<p>• Contar con profesionales idóneos que permitan vincular una educación pertinente para estudiantes con diferentes ritmos de aprendizaje.</p>
<p>• Contribuir a mejorar la calidad de vida de las estudiantes mediante campañas, dinámicas, recreación y actividades divertidas.</p>
<p>• Fomentar mecanismos de inclusión desde todos los ámbitos, diseñando estrategias con personal especializado.</p>
<p>• Recibir con alegría a las estudiantes con NEE, presentándoles la institución como el mejor lugar para aprender.</p>
<p>• Elaborar y ejecutar proyectos que apoyen el desarrollo de estudiantes con dificultades y necesidades especiales.</p>
<p>• Establecer convenios institucionales para favorecer el desarrollo y disminuir dificultades, asegurando que las estudiantes alcancen los logros mínimos.</p>
<p>• Trabajar conjuntamente con las familias como apoyo en el proceso de inclusión.</p>
<p>• Brindar y recibir capacitaciones permanentes para trabajar con estudiantes con NEE.</p>
<p>• Diseñar clases basadas en las necesidades educativas especiales y las preferencias de las estudiantes para una formación integral y personalizada.</p>
<p>• Concientizar a los padres de familia sobre las dificultades que enfrentan sus hijas y comprometerlos en el proceso de apoyo.</p>
<p>• Incorporar personal capacitado para trabajar con docentes y familias en la inclusión educativa.</p>
<p>• Diseñar acciones articuladas que creen igualdad entre estudiantes con necesidades especiales, fomentando actividades que desarrollen sus talentos.</p>
<p>• Aprovechar las acciones gubernamentales para diseñar proyectos con talleres participativos que fortalezcan valores espirituales, sociales y disciplinarios.</p>
<p>• Elaborar proyectos de música y arte, además de concursos de lectura e interpretación, fomentando la lectura permanente en todas las áreas.</p>
<p>• Crear espacios recreativos para exponer trabajos realizados por estudiantes durante el año escolar.</p>
<p>• Dar prioridad a la convivencia entre docentes y estudiantes para promover la integración.</p>
<p>• Realizar conversatorios frecuentes para fomentar el trabajo cooperativo e incluyente, descubriendo habilidades y guiándolas en proyectos educativos.</p>
<p>• Establecer alianzas con instituciones para fortalecer los lazos de apoyo y acompañamiento.</p>
<p>• Fortalecer el espíritu espiritual de las estudiantes mediante convivencias y actividades religiosas como eucaristías.</p>
<p>• Instalar cámaras en todas las aulas para prevenir casos de abuso y garantizar la seguridad física, moral y psicológica.</p>
<p>• Establecer proyectos para potenciar las capacidades excepcionales y desarrollar habilidades de estudiantes con dificultades de pensamiento.</p>
<p>• Contar con personal capacitado para evaluar y proponer planes de desarrollo que impulsen las potencialidades de las estudiantes.</p>
<p>• Promover valores de respeto hacia la diferencia y el uso correcto de los derechos de las estudiantes con NEE.</p>
<p>• Fomentar la participación activa de la comunidad educativa en los lineamientos de la institución mediante un buzón de sugerencias.</p>
<p>• Crear un espacio con un especialista en salud para garantizar la salud física y mental de las estudiantes con NEE.</p>
<p>• Fortalecer el uso de vídeos y talleres que amplíen el bienestar físico, emocional y sexual de las estudiantes.</p>
<p>• Asegurar que la institución esté en capacidad de atender diferentes ritmos de aprendizaje a través de la formación constante de docentes y directivos.</p>
</ul>

<p><h1>Componentes Transversales:</p></h1>
<ul>
<p>• Por ello, la IE tiene un gran componente de transversalidad, el Desarrollo Humano, que no solamente es considerada área optativa, sino como proyecto de vida personal y social, que apunta a la formación del SER trascendente, humano y respetuoso de la convivencia, en la estudiante teresiana. Por ello, se usan con frecuencia:</p>
<p>• El trabajo en equipo: esta competencia consiste en “Trabajar en coordinación con otros según acuerdos y metas establecidas para lograr un objetivo compartido”; al mismo tiempo, implica un esfuerzo de concertación para llegar a metas comunes, formas de trabajo y mecanismos para regular el comportamiento.</p>
<p>• El análisis de problemas: se basa en la obtención de información sobre un problema con el fin de identificarlo, estudiar las causas que lo están generando y organizar esta información para obtener una solución, siendo necesario actuar y tomar decisiones.</p>
<p>• La investigación: se concibe como un proceso constante y participativo donde se buscan respuestas a las preguntas que la cotidianidad va suscitando y se evalúa tanto el proceso como el producto.</p>
</ul>
<p><h1>Metodología:</p></h1>
<ul>
<p>• Las asignaturas se organizan de tal forma que conlleven a las estudiantes a pensar de forma creativa; el maestro contribuye a organizarlas para que ellas promuevan su creatividad, competencias y desarrollo intelectual. Las actividades se organizan en forma cíclica, con aumento de complejidad acordes al período de desarrollo de las niñas, desde el juego en la edad escolar hasta las actividades sociales de la adolescente. En el aprendizaje se da primero la asimilación de conocimientos generales y abstractos, para luego familiarizarse con los conocimientos particulares y concretos. Los recursos son los correspondientes a cada actividad.</p>
<p>• Para el diseño del currículo, se analiza la realidad social y, de forma transversal e integral, se selecciona, apropia y evalúan los conocimientos, atendiendo a los estándares y DBA que el país va construyendo para cada área y grado. Los contenidos científicos y culturales son reconstruidos, se trabaja la lengua materna (castellano) y un idioma extranjero, siguiendo las directrices de áreas obligatorias y fundamentales para Colombia y los conceptos de la ciencia y de la tecnología más convenientes al proceso de construcción del conocimiento global y local.</p>
<p>• La evaluación se realiza a la reconstrucción del conocimiento, a la capacidad de desarrollo del pensamiento de la estudiante (competencias) y la expresión en su lenguaje, en una relación SER - SABER - HACER en contexto. Se propicia la evaluación formativa, la autoevaluación, heteroevaluación y coevaluación.</p>
</ul>
<p><h1>Capacidades que se Desarrollan:</p></h1>
<ul>
<p>• Según esta teoría, los seres humanos no estamos programados culturalmente para comprender el mundo de una sola manera, y la inteligencia en cada individuo es el potencial biológico que posee y que se desarrolla en un determinado contexto socio-cultural al resolver problemas reales y elaborar productos que son importantes para esta comunidad determinada. Con ello, nuestras estudiantes estarán en capacidad de:</p>
<p>• Desarrollar sus capacidades físicas e intelectuales, en aras de alcanzar las metas que las llevarán a realizarse como personas, siendo útiles a la sociedad y al país.</p>
<p>• Despertar en ellas el gusto por saber, estudiar y aprender.</p>
<p>• Formarse como personas con sentido crítico y analítico capaces de enfrentarse a un mundo globalizado.</p>
<p>• Hacer investigación, ser trascendentales y comprometidas con su propio desarrollo, con su familia y con la sociedad en la cual están inmersas.</p>
<p>• Valorar la disciplina y el aprendizaje como medios para autorregularse y formar su carácter.</p>
<p>• Descubrirse como un ser único e irrepetible, diferente, pero con una proyección social.</p>
<p>• Tomar decisiones con un criterio de responsabilidad y optimismo, porque son seres libres.</p>
<p>• Amar profundamente su vida y la de los demás, como el valor más sagrado que todos tenemos y que debemos cultivar.</p>
<p>• Valorar la familia como una institución donde nos formamos como personas, nos educamos en la fe, moral y nos proyectamos al desarrollo y cambio social.</p>
<p>• Ser personas de trascendencia en el nivel humano y espiritual.</p>
<p>• Valorar el trabajo como factor de humanización y de liberación integral.</p>
<p>• Tener y crear una conciencia ecológica en nosotros y en los demás, asumiendo actitudes concretas de responsabilidad, promoviendo la protección del medio ambiente.</p>
</ul>

<li><a href="#">Menú</a></li>

</ul>
     <h1 id="capitulo-IV">Actores Fundamentales</h1>

<p>CAPITULO IV</p>

<ul>
<p>En esta tarea de hacer vida la Filosofía de la institución, intervienen cuatro actores fundamentales:</p>
<p><h1>Perfil de las Estudiantes:</h1><p> 
<p>Son el centro y sujeto activo del proceso educativo, en función de la cual, todo debe girar. (Debido a que las estudiantes son el eje central de nuestro quehacer educativo, ellas tendran un capitulo aparte para su perfil.)</p>


<p><p><h1>Perfil del Docente:</h1><p>
<p>El docente ejerce el rol de mediador de los aprendizajes, establece una relación intencionada y significativa con los estudiantes, encargándose de potenciar en ellos las capacidades que no pueden desarrollarse de forma autónoma (Zona de Desarrollo Próximo). Se encarga de seleccionar, organizar y planificar los contenidos, variando su frecuencia y amplitud, según diferencias individuales, para garantizar reflexiones y procesos de «reorganización cognitiva», con el ejercicio y desarrollo de funciones y operaciones de pensamiento que orienten la elaboración de conclusiones. Tiende a lograr que las estudiantes conozcan su propia realidad y adquieran aprendizajes sustentados en el análisis de la problemática social y comunitaria. Se orienta al desarrollo del pensamiento crítico-reflexivo que permite que la estudiante, en un proceso de reflexión-acción, logre incorporarse en el proceso de transformación social, todo esto a través del uso de la lectura y la escritura para potenciar la verbalización socializadora.</p>
<ul>
<p><h1>1. Formador integral</h1><p>
<p>Ser formador de personas libres de pensar, hacer, querer, afrontar y solucionar sus problemas y los de la sociedad o entorno donde vive.</p>
<p>Direccionar su práctica pedagógica al respeto a la persona y a la diferencia, a la vida, a la libertad y la honestidad.</p>
<p>Tener como objetivo la formación integral de las estudiantes y la convivencia con los demás en armonía.</p>
<p>Formar una mujer comprometida con su formación, crecimiento y promoción integral, capaz de producir transformación en su entorno familiar y social.</p>
<p>Impartir formación a mujeres con esperanza, en resiliencia, con base en la interdisciplinariedad del conocimiento contextualizado, para que crezcan en valores espirituales.</p>

<p><h1>2. Mediador pedagógico</h1><p>
<p>Promover en las estudiantes el gusto por estudiar y aprender.</p>
<p>Permitir a las estudiantes enfrentarse a situaciones difíciles y contribuir al crecimiento de su entorno familiar y social.</p>
<p>Tener gusto por descubrir y construir el conocimiento, buscando la razón a lo que sabe.</p>
<p>Formar a la persona en todas sus dimensiones espirituales con un sentido de investigación trascendental.</p>

<p><h1>3. Compromiso ético</h1><p>
<p>Ser una persona honesta, crítica, cuestionadora, conocedora de su propia cultura y del mundo globalizado.</p>
<p>Asumir con responsabilidad el compromiso con la comunidad educativa, conservando su integridad ética y moral para dedicarse a la formación de la estudiante.</p>
<p>Ser comprometido, responsable, con principios y valores, dispuesto a ser y crecer como persona exitosa.</p>

<p><h1>4. Cultura inclusiva</h1><p>
<p>Manejar los fundamentos epistemológicos, antropológicos, sociológicos y pedagógicos para brindar una educación que responda a las realidades del entorno.</p>
<p>Formación para atender estudiantes con Necesidades Educativas Especiales (NEE), adaptando metodologías que reconozcan los ritmos y estilos de aprendizaje.</p>
<p>Direccionar su práctica pedagógica al respeto a la persona y a la diferencia, fomentando la inclusión.</p>

<p><h1>5. Agente transformador</h1><p>
<p>Ser un maestro cuestionador, líder, capaz de transformar la realidad al elegir con conciencia a sus representantes (políticos).</p>
<p>Formar personas conocedoras de su cultura que puedan resolver conflictos y situaciones del lugar donde viven.</p>
<p>Formar mujeres preparadas intelectual, espiritual, tecnológica y laboralmente, que se desempeñen con eficiencia en distintos campos de la vida.</p>
<p>Promover el desarrollo de liderazgos positivos, impulsando la innovación y la transformación social mediante una pedagogía contextualizada y participativa.</p>

<p><h1>6. Competencias profesionales</h1><p>
<p>Manejar los fundamentos epistemológicos, antropológicos, sociológicos y pedagógicos para brindar una educación que responda a las realidades del entorno.</p>
<p>Formar personas con sentido crítico y analítico, capaces de enfrentarse a un mundo globalizado.</p>
<p>Asumir con responsabilidad el compromiso con la comunidad educativa, conservando su integridad ética y moral para dedicarse a la formación de la estudiante.</p>
<p>Direccionar su práctica pedagógica al respeto a la persona, la vida, la libertad y la honestidad.</p>
</ul>

<p><h1>Perfil de los Padres de Familia</h1><p>
<ul>
<p>EL PADRE DE FAMILIA: Corresponsable de la formación de su hija, responsable directo del comportamiento de su hija a nivel del hogar y socialmente, donde proyecta su aprendizaje educativo.</p>
Perfil de Padres de Familia
<p>Corresponsabilidad educativa: Acompañan activamente el proceso formativo de sus hijas, promoviendo valores en el hogar y reforzando el aprendizaje adquirido en la institución..</p>
<p>Modelo de convivencia: Promueven la tolerancia, el respeto y la solidaridad, tanto en el entorno familiar como en las relaciones con la comunidad educativa..</p>
<p>Compromiso con la institución: Participan en actividades y talleres que fortalezcan la relación familia-escuela, respetando y apoyando las normas del Manual de Convivencia..</p>
<p>Fomento de valores en el hogar: Inculcan valores esenciales como el respeto, la solidaridad y la tolerancia, reforzando el ambiente de aprendizaje desde casa..</p>
<p>Vigilancia y apoyo educativo: Supervisan el rendimiento académico y personal de sus hijas, fomentando hábitos de estudio y apoyando en áreas específicas de mejora..</p>
<p>Compromiso con la convivencia escolar: Respaldan y aplican las normas de convivencia, sirviendo como ejemplo de ética y responsabilidad..</p>
</ul>
<p><p><h1>Aliados formativos:</h1><p>
<ul>
 Perfil de Aliados Formativos
<p>Sostenibilidad social: Participan en proyectos y actividades que refuercen la identidad cultural y el cuidado del medio ambiente, alineados con los valores y objetivos institucionales..</p>
<p>Compromiso comunitario: Trabajan conjuntamente en la mejora del entorno social y educativo de las estudiantes, fortaleciendo la relación entre la institución y la sociedad..</p>
<p>Liderazgo ético: Impulsan el bienestar común mediante la construcción de espacios de diálogo, convivencia y solución pacífica de conflictos.
<p>Participación en proyectos institucionales: Colaboran en actividades que fomenten los valores convivenciales y el desarrollo cultural de las estudiantes.
<p>Promotores del desarrollo sostenible: Lideran actividades que protejan el medio ambiente y promuevan prácticas responsables, en concordancia con los principios institucionales.
<p>Liderazgo en procesos comunitarios: Generan espacios que fortalezcan los vínculos entre la institución y la comunidad, fomentando la inclusión y el respeto mutuo.

<p>Estas características fortalecen el enfoque integral de la institución educativa, promoviendo una colaboración activa y sostenible entre todos los actores involucrados.<ul>
</ul>
</ul>
<p><h1>Perfil de la Comunidad Educativa</h1><p>
<ul>
<p>La sociedad: Donde la alumna vive de una manera práctica los valores asimilados en el hogar y en la institución; confrontándose de esta manera, como SER persona en medio de ella.</p>
<p>Actores integradores: Promueven un ambiente escolar inclusivo, respetuoso y seguro, donde todos los miembros contribuyan al desarrollo integral de las estudiantes..</p>
<p>Sostenibilidad social: Participan en proyectos y actividades que refuercen la identidad cultural y el cuidado del medio ambiente, alineados con los valores y objetivos institucionales..</p>
<p>Compromiso comunitario: Trabajan conjuntamente en la mejora del entorno social y educativo de las estudiantes, fortaleciendo la relación entre la institución y la sociedad..</p>
<p>Liderazgo ético: Se comprometen a impulsar el bienestar común mediante la construcción de espacios de diálogo, convivencia y solución pacífica de conflictos..</p>
<p>Cultura de inclusión y equidad: Respetan y valoran la diversidad étnica, cultural y de género, fomentando la participación activa de todos los miembros de la comunidad..</p>
</ul>


<li><a href="#">Menú</a></li>

</ul>
     <h1 id="capitulo-V">Deberes y derechos de las Estudiantes</h1>
<p><p><h1>Perfil de la Estudiante:</h1><p>
<p>CAPITULO V</p>

<p>La institución espera formar una (mujer) persona humana, trascendente, consciente de su desarrollo y crecimiento físico, afectivo, intelectual, moral y espiritual; que sea autónoma; que se autoestime y conozca sus deberes y derechos; abierta al cambio, comprometida con los demás y constructora de la comunión, participación y trabajo colaborativo; consciente de su dignidad y la de los demás; que de acuerdo a los códigos de la modernidad potencie su capacidad para:</p>
<p>Analizar críticamente el entorno social, para insertarse en él de manera activa y productiva.</p>
<p>Recepcionar críticamente la información de los medios de comunicación social.</p>
<p>Planear, organizar, trabajar y decidir en equipo.</p>
<p>Aplicar, ubicar, acceder y usar mejor la información acumulada desde los distintos diálogos de saberes.</p>

<p><h1>Diagnostico</p></h1>
<ul>
<p>Las estudiantes de la IE Santa Teresita, en un alto porcentaje, son afros, de gran belleza física y algunas en situación de discapacidad con fortalezas como son: alegres, amigables, abiertas al diálogo, espontáneas, expresivas, extrovertidas, femeninas, amorosas del arte, hábiles bailarinas, colaboradoras, afectivas, ahorradoras, creativas, críticas, coquetas, curiosas, delicadas, espirituales, astutas, autónomas, con diferentes ritmos de aprendizaje, amantes de las fiestas y el jolgorio, con grandes capacidades intelectuales, con gusto por el buen vestir, ingeniosas, inquietas, inteligentes, respetuosas de su intimidad, con sentido de pertenencia, investigadoras, leales, líderes, mediadoras en los conflictos, receptivas, respetuosas de sí mismas y de los demás, responsables, románticas, sencillas, sinceras, solidarias, talentosas, tolerantes.</p>
<p>Sin embargo, persiste una minoría que presenta manifestaciones y actitudes que dificultan la convivencia y el desarrollo de su formación integral, como se pretende en el horizonte institucional.</p>
</ul>
<p><h1>Principios de Formación</p></h1>
<ul>
<p>Todos los actos y procesos institucionales de educación pertinente, hacia la calidad, propenden por formar a la estudiante teresiana con base en los siguientes principios:</p>
<p>La I.E. Santa Teresita será facilitadora de la formación de mujeres, seres humanos comprometidas, autónomas que visualicen y que emerjan en un mundo que está en constante cambio, sin que éstos las absorban.</p>
<p>La I.E. Santa Teresita propende por una educación en la que se permita el pleno desarrollo de la personalidad de la niña (como individuo y sujeto social) fomentando y promoviendo un proceso de desarrollo infantil, (pre-escolar), armónico, integral en los aspectos físicos y psicológicos, basado siempre sobre derechos y bienestar de las niñas. Posteriormente, la joven lo hará desde todos los procesos integrales de la Básica y la media.</p>
<p>La Institución Educativa Santa Teresita basa su filosofía en la formación de la persona en forma integral teniendo en cuenta los valores personales, espirituales, sociales, culturales, económicos para hacer de ella un ser trascendente, útil a su familia y la sociedad.</p>
<p>La formación de la persona, abarca: el ser, el saber, el saber hacer y el saber convivir teniendo en cuenta el contexto social, educación con todos sus valores, para que sea agente de cambio, fortalecida y con ayuda de todas sus dimensiones.</p>
<p>El gusto y el interés de la estudiante por aprender, debe partir de los estímulos que se le den, que no solamente sean como un paseo, una medalla, u otros bienes materiales tangibles; sino inmateriales como la comprensión y el afecto basado en una sonrisa y la tolerancia, teniendo en cuenta que como humanos fallamos.</p>
<p>Las personas, docentes y directivos que dinamizan, dirigen y orientan dicho proceso de formación integral, son trabajadores de vocación, con grandes cualidades humanas y profesionales; en constante profesionalización, superación y aprendizaje.</p>
<p>La base de formación integral de las personas, es en todas sus dimensiones: cognitiva, espiritual, social, productiva, democrática, ética y en valores, que sepa vivir y convivir, que sea capaz de pensar y apropiarse del conocimiento, competente, generadora de cambios, haciendo énfasis en la participación crítica que ayuda a transformar su entorno, siendo útiles a la sociedad, que puedan cambiar y vivir con los cambios actuales, utilizando todas las dimensiones del ser humano, procesos, aplicaciones, desde la creatividad y los recursos del medio o los que estén a su alcance, evaluando constantemente.</p>
<p>La formación espiritual del ser, debe hacerse sin perder de vista los valores fundamentales como el respeto, la responsabilidad, los principios éticos y morales y demás valores que en consenso se asuman; desde la fe cristiana católica, evitando que se pierda y con ella, la razón del ser institucional; en respeto de otras confesiones religiosas y siempre hacia la adquisición de actitudes deseables para la construcción de una persona idónea para la convivencia y el respeto mutuo de las diferencias, cumplidora de sus deberes y de los derechos de los demás.</p>
<p>Crear en sus estudiantes un espíritu transformador, partiendo del conocimiento interdisciplinar, inter-áreas, en diálogo de saberes de manera constante, la participación crítica y la formación en valores, para que sea comprometida consigo mismo y la sociedad.</p>
<p>El Trabajo cooperativo siempre será desde los valores, hacia la consecución de una Educación de calidad, transformadora de las condiciones de vida, actuales y futuras, en total respeto de la vida personal y la de los demás.</p>
<p>La formación apunta hacia la consolidación de una persona autónoma que: Tome posesión dentro del mundo donde se desenvuelve; que sepa hacer las cosas y las haga bien, que pueda resolver sus propios problemas y ayude a otros; que sea recursiva, que haga las cosas a tiempo, competitiva, en un mercado que cada día exige más.</p>
<p>La educación teresiana, incluye la formación de la estudiante con una amplia visión del mundo, integrada de manera productiva a la sociedad, con grandes valores y capaz de tener un trato amable y cortés con las personas con quienes se desenvuelve, en su quehacer diario. Activa, impulsadora de proyectos que lleven al municipio a un desarrollo cada vez mayor.</p>
<p>La I. E. Santa Teresita deberá promover estudiantes íntegros (críticos – analíticos – competentes) con pensamientos progresivos en pos del desarrollo de la comunidad.</p>
<p>Tener en cuenta a la estudiante en todas sus dimensiones para que sienta gusto por saber descubrir y construir conocimiento, reconocer, valorar y conservar su identidad étnica desde la pluralidad cultural.</p>
<p>La corporatividad del trabajo institucional, consiste en funcionar como un cuerpo, lo que implica y exige la corresponsabilidad de los diferentes estamentos que conforman la comunidad.</p>
<p>Formación espiritual – social – cultural e integral en nuestras estudiantes dando prioridad al ser humano como persona para establecer relaciones con el mundo, la naturaleza y la sociedad a través de sus conocimientos, desarrollo de las habilidades y destrezas formando en ellas actitudes de cambio para su propia transformación y la de su contexto socio-histórico-cultural.</p>
</ul>

<p><h1>Deberes y Derechos</p></h1>

<p><h1>Deberes</p></h1>
<ul>
<p>Las estudiantes deben:</p>
<li>Respetar los horarios y normas establecidas por la institución.</p>
<li>Asistir con el uniforme completo y apropiado según las actividades.</p>
<li>Respetar a todos los miembros de la comunidad educativa.</p>
<li>Cuidar los bienes y espacios comunes de la institución.</p>
<li>Participar activamente en proyectos y programas escolares.</p>
<li>Mantener un comportamiento respetuoso y evitar conductas agresivas.</p>
<li>Respetar el juego y recreación de las compañeras en el patio.</p>
<li>Evitar el uso de dispositivos móviles durante las clases, salvo autorización expresa.</p>
</ul>

<p><h1>Derechos</p></h1>
<ul>
<p>Las estudiantes tienen derecho a:</p>
<li>Recibir una educación de calidad con equidad y participación.</p>
<li>Ser escuchadas y respetadas como personas únicas.</p>
<li>Acceder a un ambiente escolar limpio y adecuado para el aprendizaje.</p>
<li>Expresarse libremente siempre que no ofenda a terceros.</p>
<li>Conocer los resultados de sus evaluaciones oportunamente.</p>
<li>Recibir apoyo psicopedagógico cuando presenten necesidades educativas especiales.</p>
<li>Participar en actividades escolares en igualdad de condiciones.</p>
</ul>


<p><h1>Niveles Educativos</p></h1>
<ul>
<li>Al culminar los distintos niveles educativos (transición, básica y media), las estudiantes alcanzan logros específicos y reciben certificaciones que reconocen sus avances académicos y preparan el camino para los niveles educativos siguientes:</p>
<li>Nivel de Transición: Al finalizar el nivel de transición (educación preescolar), las estudiantes reciben una certificación de aprobación que indica que han completado esta etapa. Se enfocan en el desarrollo de habilidades básicas y sociales, preparándolas para ingresar a la educación básica primaria.</p>
<li>Educación Básica (Primaria y Secundaria): Al finalizar la educación básica, que incluye primaria (grados 1º a 5º) y secundaria (grados 6º a 9º), las estudiantes reciben una certificación de finalización de la educación básica. Esto marca el cumplimiento de los objetivos educativos y les permite avanzar hacia la educación media.</p>
<li>Educación Media: Al culminar la educación media (grados 10º y 11º), las estudiantes que cumplen con todos los requisitos académicos y disciplinarios obtienen el título de Bachiller Académico, permitiéndoles optar por la educación superior o ingresar al mercado laboral.</p>
<li>Cada certificación es emitida por la institución educativa y cumple con los requisitos estipulados por el Ministerio de Educación Nacional.</p>
</ul>

<p><h1>Para aspirar al título de Bachiller Académico</p></h1>

Según la Ley 115 de 1994 (Ley General de Educación) y la Ley 1620 de 2013 (Ley de Convivencia Escolar), existen disposiciones que podrían impedir que un estudiante de undécimo grado asista a la ceremonia de graduación. Estas incluyen:</p>
<ul>
<li>Incumplimiento de requisitos académicos: Las estudiantes deben cumplir con los objetivos y áreas obligatorias del plan de estudios para obtener el título de bachiller.</p>
<li>Faltas disciplinarias graves: Actos de violencia, acoso escolar o comportamientos que atenten contra la convivencia escolar pueden conllevar sanciones que incluyan la suspensión de actividades como la ceremonia de graduación.</p>
<li>Incumplimiento de normas institucionales: Faltas como inasistencias injustificadas o irrespeto hacia docentes o compañeros pueden afectar la participación en eventos institucionales.</p>
<li>Todas las medidas disciplinarias deben garantizar el debido proceso y el derecho a defensa de las estudiantes.</p>
</ul>

<li><a href="#">Menú</a></li>

</ul>

     <h1 id="capitulo-VI">Gobierno Escolar</a></h1>

<p>CAPITULO VI</p>

<p>El gobierno escolar está constituido por los siguientes órganos:</p>
<ul>
<p>El Consejo Directivo: como instancia directiva de participación de la comunidad educativa y de orientación académica y administrativa del establecimiento.</p>
<p>El Consejo Académico: como instancia superior para participar en la orientación pedagógica del establecimiento.</p>
<p>El Rector: como representante del establecimiento ante las autoridades y ejecutor de las decisiones del gobierno escolar.</p>
</ul>
<p><h1>Consejo Directivo</p></h1>
<ul>
<p>Se conforma en los primeros 60 días del calendario escolar, sus representantes salen de reuniones convocadas por el Rector, para cada uno de los estamentos que lo conformen; la selección se hace por voluntad propia o candidatizando personas para hacer luego votación en público, su período será por un año.</p>
<p>Integrantes del Consejo Directivo: (Decreto 1860, Art.21 de 1994)</p>
<p>El rector quien preside y convoca.</p>
<p>Dos docentes, un representante de la básica primaria y otro de la básica secundaria y media.</p>
<p>Un representante de las estudiantes, que se encuentre cursando el último grado de educación ofrecido por la institución, elegido por el consejo de estudiantes.</p>
<p>Dos representantes de los padres de familia o acudiente, elegidos del consejo de padres, al no estar constituida legalmente la Asociación de Padres de Familia.</p>
<p>Un representante de los exestudiantes, elegido por el Consejo Directivo, de ternas presentadas por las organizaciones que aglutinen la mayoría de ellos o en su defecto, por quien haya ejercido en el año inmediatamente anterior el cargo de representante de las estudiantes.</p>
<p>Un representante de los sectores productivos organizados en el ámbito local o subsidiariamente de las entidades que auspicien o patrocinen el funcionamiento del establecimiento educativo. El representante será escogido por el Consejo Directivo, de candidatos propuestos por las respectivas organizaciones.</p>
</ul>

<p><h1>Funciones del Consejo Directivo:</p></h1>
<ul>
<p>(Decreto 1860/94, Art.23. Decreto 4791/2008, Decreto 1290/2009)</p>
<p>• Tomar las decisiones que afecten el funcionamiento de la institución, excepto las que sean competencia de otra autoridad tales como las reservadas a la Secretaría de Educación.</p>
<p>• Servir de instancia para resolver conflictos que se presenten entre docentes y administrativos con los estudiantes del establecimiento educativo y después de haber agotado los procedimientos previstos en el reglamento o manual de convivencia.</p>
<p>• Adoptar el manual de convivencia y el reglamento de la institución.</p>
<p>• Fijar los criterios para la asignación de cupos disponibles para la admisión de nuevas alumnas.</p>
<p>• Asumir la defensa y garantía de los derechos de toda la comunidad educativa, cuando alguno de sus miembros, se sientan lesionados.</p>
<p>• Aprobar el plan anual de actualización académica del personal docente presentado por el rector.</p>
<p>• Participar en la planeación y evaluación del Proyecto Educativo Institucional, del currículo y del plan de estudio y someterlo a la consideración de la Secretaria de Educación o del organismo que haga sus veces, para que verifiquen el cumplimiento de los requisitos establecidos en la Ley y los reglamentos.</p>
<p>• Estimular y controlar el buen funcionamiento de la institución educativa.</p>
<p>• Establecer estímulos y sanciones para el buen desarrollo académico y social de la estudiante, que ha de incorporarse al reglamento o manual de convivencia. En ningún caso pueden ser contrarios a la dignidad del estudiante.</p>
<p>• Recomendar criterios de participación de la institución en actividades comunitarias, culturales, deportivas y recreativas.</p>
<p>• Establecer el procedimiento para permitir el uso de las instalaciones en la realización de actividades educativas, culturales, recreativas, deportivas y sociales de la comunidad educativa.</p>
<p>• Promover las relaciones de tipo académico, deportivo y cultural con otras instituciones educativas y la conformación de organizaciones juveniles.</p>
<p>• Fomentar la conformación de asociaciones de padres de familia y de estudiantes.</p>
<p>• Reglamentar los procesos electorales previstos en el decreto 1860/94.</p>
<p>• Aprobar el presupuesto de ingresos y gastos de los recursos propios y provenientes de pagos legalmente autorizados, efectuados por los padres y responsables de la educación de los estudiantes, tales como derechos académicos, uso de libros de textos y similares.</p>
<p>• Decidir sobre la promoción anticipada de estudiantes presentado por el Consejo Académico durante el primer período del año escolar.</p>
<p>• Servir de instancia para decidir sobre reclamaciones que presenten las estudiantes o sus padres de familia en relación con la evaluación promoción.</p>
<p>• Aprobar el sistema institucional de evaluación (SIE) de las estudiantes.</p>
<p>• Antes del inicio de cada año escolar, analizar, introducir ajustes y aprobar mediante acuerdo el presupuesto de ingresos y gastos del proyecto presentado por el rector.</p>
<p>• Adoptar el reglamento para el manejo de la tesorería, el cual por lo menos determinará la forma de realización de los recaudos y de los pagos, según la normatividad existente en la entidad territorial certificada, así como el seguimiento y control permanente al flujo de caja y los responsables en la autorización de los pagos.</p>
<p>• Aprobar las adiciones al presupuesto vigente, así como los traslados presupuestales que afecten el mismo.</p>
<p>• Verificar la existencia y presentación de los estados contables por parte del rector, elaborados de acuerdo con las normas contables vigentes expedidas por el Contralor General de la nación, con la periodicidad señalada por los organismos de control.</p>
<p>• Determinar los actos o contratos que requieran su autorización expresa.</p>
<p>• Reglamentar mediante acuerdo los procedimientos, formalidades y garantías para toda contratación que no supere los veinte (20) salarios mínimos legales vigentes.</p>
<p>• Aprobar la contratación de los servicios que requiera el establecimiento educativo y que faciliten su funcionamiento de conformidad con la ley.</p>
<p>• Autorizar al rector para la utilización por parte de terceros de los bienes muebles o inmuebles dispuestos para el uso del establecimiento educativo, bien sea gratuita o con cobros, previa verificación del procedimiento establecido por dicho órgano escolar de conformidad con lo dispuesto en el decreto 1860 de 1994.</p>
<p>• Aprobar la utilización de recursos del Fondo de Servicio Educativo para la realización de eventos pedagógicos, científicos, culturales, deportivos, o la participación de los educandos en representación del establecimiento educativo y fijar la cuantía que se destine para tal efecto.</p>
<p>• Verificar el cumplimiento de la publicación en lugar visible y de fácil acceso del informe de ejecución de los recursos del Fondo de Servicios Educativos.</p>
<p>• Darse su propio reglamento.</p>
</ul>

<p><h1>Consejo Académico</p></h1>
<ul>
<p>• Conformación del Consejo Académico: (Artículo 24 Decreto 1860).</p>
<p>• El Consejo Académico está integrado por el Rector quien lo preside y convoca, un docente por cada una de las áreas en la básica secundaria y media, un docente por el preescolar y un representante de 3° a 5° de primaria y los coordinadores.</p>
<p>• Los docentes se eligen en asamblea durante el primer mes del período lectivo anual. El período será de un año lectivo. Sesionará ordinariamente al inicio y finalización del año escolar y al fin de cada uno de los cuatro períodos académicos y en el informe final. Se reunirá extraordinariamente, cuando se presente una novedad académica a solicitud del Consejo de Estudiantes, de profesores o de padres de familia.</p>

<p><h1>Funciones del Consejo Académico:</p></h1>
<p>(Decreto 1860/1994, art.24)</p>
<ul>
<p>• Proponer el currículo de la institución educativa y la orientación en el desarrollo de la calidad educativa.</p>
<p>• Promover y adoptar el sistema institucional de evaluación y su aplicación.</p>
<p>• Servir de instancia para evaluar el desempeño académico de los docentes y su trabajo en el aula.</p>
<p>• Adoptar y ajustar el manual de convivencia y reglamento de estudiantes, en coordinación con el Consejo Directivo.</p>
<p>• Discutir y analizar la planeación de la evaluación de los aprendizajes y establecer criterios de evaluación por períodos.</p>
<p>• Conocer y analizar las evaluaciones y resultados académicos por estudiantes y asignaturas.</p>
<p>• Conocer las inquietudes de las estudiantes y de los padres de familia respecto a la orientación de la calidad académica.</p>
<p>• Definir criterios de recuperación y promoción.</p>
<p>• Proponer al Consejo Directivo los ajustes que requiera el proyecto educativo institucional y su respectiva formulación.</p>
<p>• Revisar los planes de mejoramiento académicos.</p>
<p>• Realizar seguimiento a la ejecución del plan de mejoramiento.</p>
<p>• Promover la utilización de recursos para actividades pedagógicas.</p>
<p>• Conocer las condiciones de funcionamiento de la institución educativa y proponer acciones de mejora.</p>
<p>• Establecer criterios para el acceso a la educación de la población vulnerable.</p>
<p>• Conocer y evaluar las propuestas que presente el consejo de estudiantes sobre los procesos académicos de la institución.</p>
<p>• Promover acciones que estimulen el desarrollo de habilidades y capacidades de las estudiantes en el marco de su formación integral.</p>
<p>• Atender inquietudes académicas y solicitar el acompañamiento de padres de familia, estudiantes y educadores.</p>
</ul>

<p><h1>EL RECTOR</p></h1>
<ul>
<p>El rector es la máxima autoridad administrativa y académica de la institución educativa, es quien coordina la actividad institucional, su dirección y su desarrollo, así como el cumplimiento de la misión y la visión del establecimiento educativo.</p>
</ul>
<ul>
<p><h1>Funciones del Rector:</p></h1>
<p>(Decreto 1860/1994, art.25)</p>
</ul>
<ul>
<p>• Ejercer la dirección y coordinación de la actividad académica del establecimiento educativo.</p>
<p>• Dirigir el funcionamiento administrativo del establecimiento.</p>
<p>• Convocar al Consejo Directivo y al Consejo Académico.</p>
<p>• Ejecutar las decisiones del Consejo Directivo.</p>
<p>• Hacer cumplir la normatividad educativa vigente.</p>
<p>• Adoptar el manual de convivencia y el reglamento del establecimiento educativo, con el respaldo del Consejo Directivo.</p>
<p>• Defender y garantizar los derechos de los estudiantes y demás miembros de la comunidad educativa.</p>
<p>• Ejecutar el plan de mejoramiento y seguimiento a la evaluación del mismo.</p>
<p>• Definir la política de evaluación y promoción de las estudiantes en articulación con el sistema institucional de evaluación.</p>
<p>• Atender a las inquietudes que tengan los estudiantes y sus padres de familia, en relación con su proceso académico.</p>
<p>• Coordinar la capacitación y formación del personal docente y administrativo.</p>
<p>• Proponer al Consejo Directivo y Consejo Académico los ajustes que requiera el Proyecto Educativo Institucional.</p>
<p>• Rendir informes de gestión ante el Consejo Directivo y a la comunidad educativa.</p>
<p>• Designar el personal administrativo y docente, de conformidad con la ley y sus normas reglamentarias.</p>
<p>• Promover las relaciones de la institución con su comunidad.</p>
<p>• Realizar el seguimiento a la ejecución del presupuesto, en relación con los recursos del establecimiento.</p>
<p>• Promover actividades de formación y convivencia de la comunidad educativa.</p>
<p>• Realizar el seguimiento a la ejecución del presupuesto.</p>
<p>• Conocer y evaluar el desempeño académico de los docentes y su trabajo en el aula.</p>
<p>• Proponer al Consejo Académico el sistema institucional de evaluación de las estudiantes.</p>
</ul>

<li><a href="#">Menú</a></li>

</ul>
</section>

    </main></p>
     <h1 id=capitulo-VII">Estamentos democráticos</a></h1>
     

<p>CAPITULO VII</p>

<p><h1>Consejo Estudiantil</p></h1>

<p>Es el máximo organismo colegiado que asegura y garantiza el continuo ejercicio de la participación por parte de los educandos.</p>
<ul>
<p><h1>Integrantes:</p></h1>

<p>• Una estudiante representante de preescolar a tercero primaria, un representante de cuarto, un representante de quinto de primaria, uno de cada grado de básica secundaria y media. Se elige de forma democrática en cada uno de los grupos por votación secreta o pública, durante el primer mes del año lectivo, para un período anual.</p>
<p>• Funciones del Consejo Estudiantil:</p>
<p>• Darse su propia organización interna.</p>
<p>• Elegir el representante de las estudiantes ante el Consejo Directivo del establecimiento y asesorarlo en el cumplimiento de su representación.</p>
<p>• Invitar a sus deliberaciones a aquellas estudiantes que presenten iniciativas sobre el desarrollo de la vida estudiantil.</p>
<p>• Las demás actividades afines o complementarias con las anteriores que le atribuya el manual de convivencia.</p>


<p><h1>Asamblea de Padres de Familia(Decreto 1286 de 2005, Art. 4)</p></h1>

<p>• La Asamblea General de Padres de Familia está conformada por todos los padres de familia del establecimiento educativo, quienes son responsables del ejercicio de sus deberes y derechos en relación con el proceso educativo de sus hijos. Debe reunirse al menos dos veces al año por convocatoria del rector.</p>

<p><h1>Consejo de padres de familia(Decreto 1286 de 2005, Art. 5)</p></h1>

<p>• Es un órgano de participación de los padres de familia destinado a asegurar su continua participación en el proceso educativo y a elevar los resultados de calidad del servicio.</p>

<p><h1>Funciones del Consejo de Padres:</p></h1>

<p>• Contribuir con el rector en el análisis y difusión de los resultados de evaluaciones.</p>
<p>• Exigir la participación de todos los estudiantes en las pruebas de Estado.</p>
<p>• Apoyar actividades artísticas, científicas, recreativas y deportivas.</p>
<p>• Participar en la elaboración de planes de mejoramiento.</p>
<p>• Promover actividades de formación para los padres de familia.</p>
<p>• Propiciar un clima de confianza y concertación en la comunidad educativa.</p>
<p>• Presentar propuestas de mejoramiento del Manual de Convivencia.</p>
<p>• Colaborar en la promoción de la salud física y mental de los educandos.</p>

<p><h1>Revocatoria de funciones:</p></h1>
<p>Término de mandato: Al finalizar el período establecido.</p>
<p>Renuncia voluntaria: Por razones personales o laborales.</p>
<p>Incumplimiento de deberes: Si no cumple con las responsabilidades asignadas.</p>

<p><h1>Elección de los representantes de los Padres de Familia al Consejo Directivo</p></h1>

<p>Del Consejo de Padres de Familia, en una reunión convocada para tal fin por el rector del establecimiento educativo, se elige dentro de los primeros treinta días del año lectivo a los dos representantes de los padres de familia en el Consejo Directivo del establecimiento educativo. Los representantes de los padres de familia solo podrán ser reelegidos por un período adicional. En todo caso, los representantes de los padres ante el Consejo Directivo deben ser padres de estudiantes del establecimiento educativo.</p>
<p>Los docentes, directivos o administrativos del establecimiento educativo no podrán ser representantes de los padres de familia en el Consejo Directivo del mismo establecimiento en que laboran.</p>

<p><h1>Junta de padres  de familia(Decreto 1268 de 2005, Art. 10)</p></h1>

<p>• El rector promociona la constitución de la Junta de Padres de Familia, para lo cual cita a una asamblea constitutiva durante el primer mes del año lectivo. El rector o su delegado dirige la asamblea y establece las estrategias para elegir los nuevos cargos de la Junta Directiva. Posterior a la elección, se hace empalme con la junta anterior.</p>
<p>• Funciones de la Junta de Padres de Familia:</p>
<p>• Apoyar la ejecución del Proyecto Educativo Institucional y el Plan de Mejoramiento del establecimiento educativo.</p>
<p>• Promover la construcción de un clima de confianza, tolerancia y respeto entre todos los miembros de la comunidad educativa.</p>
<p>• Promover los procesos de formación y actualización de los padres de familia.</p>
<p>• Apoyar a las familias y a las estudiantes en el desarrollo de las acciones necesarias para mejorar sus resultados de aprendizaje.</p>
<p>• Promover entre los padres de familia una cultura de convivencia, solución pacífica de los conflictos y compromiso con la legalidad.</p>
<p>• Facilitar la solución de los problemas individuales y colectivos de los menores y propiciar acciones tendientes al mejoramiento de su formación integral de conformidad con lo establecido en el artículo 315 del Decreto 2737 de 1989.</p>

<p><h1>Obligación ética fundamental de la Institución Educativa</p></h1>

<p>• Garantizar a las niñas y adolescentes el pleno respeto a su dignidad, vida, integridad física y moral dentro de la convivencia escolar.</p>
<p>• Formar a las niñas y adolescentes en el respeto por los valores fundamentales de la dignidad humana, los derechos humanos, la aceptación y la tolerancia hacia las diferencias entre personas.</p>
<p>• Proteger eficazmente a las niñas y adolescentes contra toda forma de maltrato, agresión física o psicológica, humillación, discriminación o burla de parte de compañeros o profesores.</p>
<p>• Establecer mecanismos disuasivos, correctivos y reeducativos para impedir agresiones físicas o psicológicas.</p>

<li><a href="#">Menú</a></li>

</ul>

<h1 id="capitulo-VIII">Representantes estudiantiles</h1>

<p>CAPITULO VIII</p>

<p><h1>Personera de las estudiantes</p></h1>
<ul>
<p>• Es una estudiante que curse el último grado que ofrece la institución, elegida por todas sus compañeras para promover el ejercicio de los deberes y derechos de las estudiantes, consagrados en la Constitución Política, las leyes, los reglamentos y el manual de convivencia.</p>

<p><h1>Requisitos para ser candidata a la personería:</p></h1>
<p>• Buen nivel académico, liderazgo positivo, buenas relaciones interpersonales, buen comportamiento, sentido de pertenencia, identidad con los valores institucionales y que cumpla con el manual de convivencia.</p>

<p><h1>Funciones de la Personera de las Estudiantes:</p></h1>

<p>• Promover el cumplimiento de los derechos y deberes de las estudiantes.</p>
<p>• Recibir y evaluar quejas y reclamos que presenten las estudiantes sobre lesiones a sus derechos.</p>
<p>• Presentar ante el Rector las solicitudes necesarias para proteger los derechos de las estudiantes.</p>
<p>• Apelar decisiones del rector ante el Consejo Directivo cuando lo considere necesario.</p>
<p>• Ser vocera de las estudiantes presentando solicitudes respetuosas y oportunas.</p>

<p><h1>Revocatoria de mandato:</p></h1>

<p>• Cumplimiento del mandato: Al finalizar el período para el cual fue elegida.</p>
<p>• Renuncia voluntaria: En caso de razones personales, académicas u otras.</p>
<p>• Incumplimiento de deberes: Si no cumple con las responsabilidades asignadas.</p>
<p>• Sanción disciplinaria: Si incurre en conductas que violen el código de convivencia estudiantil.</p>
<p>• La reemplazante será quien haya quedado de segunda en votación.</p>
</ul>

<p><h1>Representante estudiantil</p></h1>
<ul>
<p><h1>¿Quién es la Representante Estudiantil?</p></h1>

<p>Es una estudiante de último grado elegida democráticamente por sus compañeras representantes de curso, para representar los intereses y opiniones del estudiantado ante el Consejo Directivo y demás instancias de la institución educativa. Su labor está orientada a promover la participación estudiantil en la toma de decisiones que afectan a la comunidad educativa.</p>

<p><h1>Requisitos para ser candidata a Representante Estudiantil:</p></h1>

<p>• Buen desempeño académico y disciplinario.
<p>• Habilidades de liderazgo y trabajo en equipo.
<p>• Buenas relaciones interpersonales.
<p>• Compromiso con los valores institucionales.
<p>• Conocimiento y respeto por el manual de convivencia.

<p><h1>Funciones de la Representante Estudiantil:</p></h1>

<p>• Representar a las estudiantes ante el Consejo Directivo y demás instancias de la institución educativa.
<p>• Velar por la defensa de los derechos e intereses del estudiantado.
<p>• Presentar propuestas y sugerencias que surjan de los estudiantes ante las autoridades escolares.
<p>• Servir de enlace entre las estudiantes y las directivas, facilitando una comunicación efectiva.
<p>• Participar activamente en la construcción de planes y proyectos institucionales que beneficien a las estudiantes.
<p>• Promover la convivencia escolar y la participación democrática en la institución.

<p><h1>Revocatoria de mandato:</p></h1>

<p>• Cumplimiento del período: Al finalizar el período para el cual fue elegida.
<p>• Renuncia voluntaria: Por razones personales, académicas u otras.
<p>• Incumplimiento de deberes: Si no cumple con las responsabilidades asignadas.
<p>• Sanción disciplinaria: Por incurrir en conductas contrarias al manual de convivencia.
<p>• La reemplazante será quien haya obtenido el segundo lugar en la votación.
</ul>

<p><h1>Contralora estudiantil</p></h1>
<ul>
<p><h1>¿Quién es la Contralora Estudiantil?</p></h1>
Es una estudiante de último grado elegida democráticamente por sus compañeras para velar por el uso eficiente y transparente de los recursos de la institución educativa, promoviendo una cultura de control social y rendición de cuentas.

<p><h1>Requisitos para ser candidata a Contralora Estudiantil:</p></h1>

<p>• Ser estudiante del último grado de la institución.
<p>• Buen desempeño académico y disciplinario.
<p>• Conocimiento básico de las funciones de control y veeduría.
<p>• Liderazgo positivo y responsabilidad.
<p>• Cumplimiento del manual de convivencia.

<p><h1>Funciones de la Contralora Estudiantil:</p></h1>

<p>• Vigilar el buen uso de los recursos de la institución educativa, promoviendo la transparencia.
<p>• Promover una cultura de participación y control social entre los estudiantes.
<p>• Presentar informes periódicos sobre la gestión de los recursos ante las directivas y la comunidad educativa.
<p>• Atender las inquietudes de las estudiantes respecto al manejo de los recursos.
<p>• Formular propuestas para mejorar la eficiencia en el uso de los recursos escolares.
<p>• Representar los intereses de las estudiantes en temas relacionados con la gestión de los recursos institucionales.

<p><h1>Revocatoria de mandato:</p></h1>

<p>• Cumplimiento del período: Al finalizar el período para el cual fue elegida.
<p>• Renuncia voluntaria: Por razones personales, académicas u otras.
<p>• Incumplimiento de deberes: Por no cumplir con sus responsabilidades asignadas.
<p>• Sanción disciplinaria: Por conductas contrarias al manual de convivencia.
<p>• La reemplazante será quien haya obtenido el segundo lugar en la votación.
</ul>


<p><h1>Representante de curso y/o Monitora estudiantil</p></h1>
<ul>
<p>• Es la estudiante escogida democráticamente por sus compañeras de clase, para ser la vocera y líder en la participación institucional.</p>

<p><h1>Requisitos:</p></h1>

<p>Buen nivel académico, buen comportamiento, no haber sido sancionada, excelentes relaciones humanas y liderazgo positivo, sentido de pertenencia, aceptación de sus compañeros, disponibilidad y colaboración.</p>

<p><h1>Funciones:</p></h1>

<p>• Informar las dificultades e inquietudes de los compañeros ante el profesor.</p>
<p>• Liderar y colaborar en las campañas de la institución.</p>
<p>• Conocer los canales de comunicación y el manual de convivencia.</p>
<p>• Informar al grupo sobre la marcha de la institución y sus actividades.</p>
<p>• Ser miembro del Consejo de Estudiantes.</p>
<p>• Estimular las buenas relaciones interpersonales en el grupo.</p>
<p>• Velar por el buen estado de los muebles y enseres del aula.</p>
<p>• Dar ejemplo de disciplina y responsabilidad.</p>

<p><h1>Revocatoria de funciones:</p></h1>

<p>• Cumplimiento de mandato: Al finalizar el período de elección.</p>
<p>Renuncia: Por razones personales o académicas.</p>
<p>Incumplimiento de deberes: Si no cumple con las responsabilidades asignadas.</p>
<p>Despido: Si infringe el código de convivencia estudiantil.</p>
<p>• La reemplazante será quien haya quedado de segunda en votación.</p>
</ul>

<li><a href="#">Menú</a></li>

<ul>


<h1 id="capitulo-IX">Obligaciones complementarias de la Institución Educativa</h1>

<p>CAPITULO IX</p>
</ul>

<ul>
<p>• Comprobar la inscripción del registro civil de nacimiento de todas las estudiantes.</p>
<p>• Establecer detección oportuna y apoyo en casos de malnutrición, maltrato, abuso sexual, violencia intrafamiliar, explotación económica, y otras formas de abuso.</p>
<p>• Comprobar la afiliación de las estudiantes a un sistema de seguridad social.</p>
<p>• Coordinar apoyos pedagógicos, terapéuticos y tecnológicos necesarios para el acceso de niñas con discapacidad.</p>
<p>• Reportar a las autoridades situaciones de abuso o maltrato.</p>
<p>• Orientar a la comunidad educativa en temas de salud sexual y reproductiva.</p>
</ul>

<p><h1>Requisitos para la matrícula de las estudiantes nuevas</p></h1>
</ul>

<p><h1>Transición:</p></h1>
<ul>

<p>• 5 años cumplidos a 31 de abril.</p>
<p>• Registro civil original.</p>
<p>• Fotocopia del SISBEN.</p>
<p>• Certificado del RH.</p>
<p>• Carnet de vacunas.</p>
<p>• Fotocopia afiliación a un sistema de salud (EPS).</p>
<p>• Fotocopia de la cédula de los padres o acudientes.</p>
<p>• Carpeta manila tipo sobre, tamaño oficio.</p>
<p>• Formato de Disponibilidad de cupo, entregado por la institución.</p>
</ul>

<p><h1>Básica Primaria y Básica Secundaria:</p></h1>
<ul>
<p>• Todos los anteriores requisitos.</p>
<p>• La edad en quinto de primaria no debe ser mayor a 12 años o su equivalente al grado.</p>
<p>• Tener buen comportamiento.</p>
<p>• Presentar ficha de seguimiento debidamente diligenciada.</p>
<p>• Cupo solicitado por el padre o acudiente y la estudiante.</p>
<p>• Certificado de calificaciones en papel membrete de la institución anterior.</p>
<p>• Las alumnas en transferencia deben estar a paz y salvo académicamente y presentar el certificado de retiro del SIMAT.</p>
</ul>

<p><h1>Media:</p></h1>
<ul>
<p>• Todos los anteriores requisitos.</p>
<p>• Edad no mayor de 18 años para cursar grado 11º.</p>
<p>• Fotocopia de documento de identidad.</p>
<p>• Certificado de calificaciones actualizadas en papel membrete de todos los años cursados.</p>
<p>• Estar a paz y salvo académicamente.</p>
<p>• Fotocopia del certificado del SISBEN.</p>
<p>• Fotocopia carnet de afiliación al sistema de salud (EPS) o seguro de salud.</p>
<p>• Solicitar la matrícula personalmente y acompañada del padre de familia o acudiente.</p>
</ul>

<p><h1>Matrícula</p></h1>
<ul>
<p>• La matrícula es el acto eminentemente pedagógico mediante el cual la comunidad educativa, la familia y la estudiante se comprometen a trabajar en forma integral para alcanzar los fines y propósitos de la educación. Con la matrícula se formaliza la vinculación de la estudiante al servicio educativo, y debe renovarse cada año.</p>
<p>• Matrícula y Renovación de la misma</p>
<p>• Los procesos de pre-matrícula, matrícula y renovación se harán cada año en las fechas definidas por la institución, actualizando datos y documentación. Las estudiantes de 1º a 11º deben renovar la matrícula acompañadas por su padre de familia o acudiente.</p>
</ul>
<p></h1>Requisitos para la renovación de la matrícula:</p></h1>
<ul>
<p>• Boletín de calificaciones del último grado cursado.</p>
</ul>

<li><a href="#">Menú</a></li>
<ul>


<h1 id="capitulo-X">El Papel de los Actores Sociales</h1>
<ul>

<li><a href="#">Menú</a></li>

<p>CAPITULO X</p>

<p><h1>El Papel de los Actores Sociales</p></h1>

<p>• El Papel de los Actores Sociales en la Gestión Pedagógica del Grupo</p>
<p>• La labor del coordinador de grupo:</p>
<p>• Su actividad fundamental es de carácter metodológico, su liderazgo le viene dado por la preparación docente y experiencia, por su habilidad en la conducción de grupos, por su labor didáctica y por el dominio de la actividad educativa.</p>
<p>• Son la columna vertebral en la que descansa el proceso de gestión pedagógica, ya que mediante su actividad tutorial gestionan la labor educativa desde el proyecto de vida escolar de las estudiantes, consignando las acciones didácticas y de carácter socio-psico-pedagógicas que garantizan el cumplimiento exitoso de este, en la medida que la satisfacción de las necesidades y aspiraciones de las estudiantes en el plano profesional y personal se acerquen al plano idealizado por estos.</p>
<p>• Mediante la atención personalizada de la labor educativa, pretenden lograr el crecimiento personal y profesional de las estudiantes, colaborando en el diseño de su proyecto de vida personal en el contexto de la actividad académica y social que hará de los mismos mejores seres humanos y con ello cumplir la misión de la educación con la sociedad.</p>
<p>• El trabajo del coordinador como gestor, líder y conductor del grupo es:</p>
<p>• Conjugar, dirigir y apoyar la labor de los docentes y del resto de las personas (organizaciones estudiantiles) vinculadas a este proceso para lograr, de común acuerdo, la gestión del proyecto de vida escolar.</p>
<p>• Colaborar en la evaluación del desempeño de estudiantes y profesores en la actividad docente educativa.</p>
<p>• Proveer los recursos técnicos para la planificación docente y la proyección estratégica del desarrollo personal de las estudiantes.</p>
<p>• Ayudar a construir un clima psico-pedagógico adecuado para resolver los conflictos entre los profesores y estudiantes y demás implicados en este proceso.</p>
<p>• Evaluar sistemáticamente la efectividad de estas tareas en la formación de las estudiantes a través del proceso de integralidad y evaluación del proyecto educativo Institucional.</p>
<p>• La labor de los profesores de las asignaturas del grado:</p>
<p>• Intervienen desde el proceso docente educativo de sus asignaturas a la planeación estratégica de los objetivos de formación:</p>
<p>• Gestionan la formación profesional y personal desde el trabajo didáctico de los contenidos (conocimientos, habilidades y valores) con los que propician la formación de actitudes profesionales y convicciones en el plano ético y social, fortaleciendo la formación vocacional y profesional, para el desempeño y el cumplimiento de los objetivos del Proyecto Educativo Institucional.</p>
<p>• Mediante la labor de orientación educativa contribuye al clima pedagógico propicio, mediante relaciones interpersonales adecuadas en las que se fortalece el carácter afectivo del proceso educativo y determina que todos los actores sociales contraigan un mayor compromiso con los resultados que se esperan y un nivel superior de responsabilidad en el desempeño de sus funciones.</p>
</ul>

<li><a href="#">Menú</a></li>

<h1 id="capitulo-XI">Sistema Nacional de Convivencia Escolar</h1>
<p>CAPITULO XI</p>
<ul>
<p>Sistema Nacional de Convivencia Escolar</p>

<p>• Sistema Nacional de Convivencia Escolar y Formación para el Ejercicio de los Derechos Humanos, la Educación para la Sexualidad y la Prevención y Mitigación de la Violencia Escolar</p>
<p>• El Comité Escolar de Convivencia</p>
<p>• El Comité Escolar de Convivencia es el encargado de apoyar la labor de promoción y seguimiento a la convivencia escolar, a la educación para el ejercicio de los derechos humanos, sexuales y reproductivos, así como del desarrollo y aplicación del manual de convivencia, de la prevención y mitigación de la violencia escolar.</p>
<p>• El Comité Escolar de Convivencia está conformado por:</p>
<p>• El rector del establecimiento educativo, quien preside el comité</p>
<p>• La personera estudiantil</p>
<p>• La psicoorientadora</p>
<p>• Los coordinadores</p>
<p>• La presidenta del consejo Estudiantil</p>
<p>• Dos docentes de Primaria</p>
<p>• Dos docentes de Secundaria</p>
<p>• Funciones del Comité Escolar de Convivencia</p>
<p>• Identificar, documentar, analizar y resolver los conflictos que se presenten entre docentes, estudiantes, directivos, y otros miembros de la comunidad educativa.</p>
<p>• Liderar acciones y estrategias que fomenten la convivencia, la construcción de ciudadanía, el ejercicio de los derechos humanos, sexuales y reproductivos, y la prevención de la violencia escolar.</p>
<p>• Promover la vinculación del establecimiento educativo a estrategias, programas y actividades de convivencia y construcción de ciudadanía.</p>
<p>• Convocar un espacio de conciliación para resolver conflictos que afecten la convivencia escolar.</p>
<p>• Activar la Ruta de Atención Integral para la Convivencia Escolar frente a situaciones de conflicto, acoso escolar o vulneración de derechos sexuales y reproductivos.</p>
<p>• Hacer seguimiento al cumplimiento del manual de convivencia y presentar informes a las instancias correspondientes del Sistema Nacional de Convivencia Escolar.</p>
<p>• Proponer estrategias pedagógicas que permitan la articulación de diferentes áreas de estudio para mejorar la convivencia escolar.</p>
<p>• Elaborar su propio reglamento de sesiones y procedimientos internos.</p>
<p>• Deberes y Obligaciones Especiales de la Institución Educativa</p>
<p>• Facilitar el acceso de las niñas y adolescentes al sistema educativo y garantizar su permanencia.</p>
<p>• Brindar una educación pertinente y de calidad.</p>
<p>• Respetar la dignidad de los miembros de la comunidad educativa en toda circunstancia.</p>
<p>• Facilitar la participación de las estudiantes en la gestión académica del establecimiento.</p>
<p>• Abrir espacios de comunicación con los padres de familia para el seguimiento del proceso educativo.</p>
<p>• Organizar programas de nivelación para estudiantes con dificultades de aprendizaje.</p>
<p>• Respetar y fomentar la expresión de las diversas culturas.</p>
<p>• Estimular la producción artística, científica y tecnológica de las estudiantes.</p>
<p>• Promover la conservación del patrimonio ambiental, cultural y nacional.</p>
<p>• Evitar cualquier conducta discriminatoria.</p>
<p>• Normas que Garantizan el Respeto entre los Miembros de la Comunidad Educativa</p>
<p>• Normas Generales de Convivencia:</p>
<p>• Presentar disculpas cuando sea necesario.</p>
<p>• Ser cortés al hacer reclamos por considerar lesionados sus derechos.</p>
<p>• Practicar normas de cortesía en la comunicación con todos los miembros de la comunidad educativa.</p>
<p>• Resolver los problemas a través del diálogo.</p>
<p>• Respetar la propiedad ajena.</p>
<p>• Conservar el medio ambiente y cuidar los recursos de la institución.</p>
<p>• Prohibición de Sanciones Crueles, Humillantes o Degradantes</p>
<p>• El rector y los docentes no podrán imponer sanciones que conlleven maltrato físico o psicológico de las estudiantes a su cargo, ni adoptar medidas que afecten su dignidad.</p>


<li><a href="#">Menú</a></li>

<h1 id="capitulo-XII">Clasificación de situaciones que afectan la convivencia escolar</h1>

<p><h1>CAPITULO XII</p></h1>

<p><h1>SITUACIONES TIPO I, II Y III</p></h1>

<p>1. SITUACIONES TIPO I</p>
<ul>
<p>• Promover el desorden en la clase, en actos comunitarios o en la calle.</p>
<p>• Comer dentro de las aulas de clase.</p>
<p>• Impuntualidad o inasistencia repetitiva a las clases.</p>
<p>• Falta de cuidado en la higiene personal.</p>
<p>• La omisión de compromisos y responsabilidades adquiridas.</p>
<p>• Uso de accesorios llamativos o extravagantes.</p>
<p>• Utilizar un vocabulario soez.</p>
<p>• Ausentarse o abstenerse sin autorización de participar en todas las actividades académicas e institucionales programadas.</p>
<p>• Discusiones o riñas entre compañeras que involucran agresiones físicas, verbales, gestuales, sin generar daños al cuerpo o a la salud.</p>
<p>• Ingresar sin autorización a dependencias de uso restringido como rectoría, secretaría, coordinación, entre otras.</p>
<p>• Agresiones verbales, gestuales o virtuales con o sin contenido sexual que hagan referencia a la orientación sexual erótica o romántica.</p>
<p>• Utilizar el celular dentro del aula de clases o en actos institucionales importantes.</p>
<p>• Dañar o alterar la decoración, carteleras o avisos educativos.</p>
<p>• Mal uso de servicios sanitarios, sillas, tableros, libros de biblioteca, entre otros recursos de la institución.</p>
<p>• Abandonar o evadirse de las instalaciones de la institución durante la jornada escolar.</p>
<p>• Menospreciar, irrespetar o ultrajar intencionalmente los símbolos patrios e institucionales.</p>
<p>• Ocasionar daños a la planta física, muebles y enseres de la institución.</p>
<p>• Comprobación de escritos o dibujos anónimos, ofensivos o insultantes.</p>
<p>• Negarse a firmar compromisos pedagógicos académicos o disciplinarios.</p>
<p>• Hacer fraudes en pruebas, exámenes o trabajos.</p>
<p>• Inducir, manipular u obligar a otra persona a realizar actos indebidos.</p>
<p>• Dejar de asistir sin autorización o permiso.</p>
<p>• Retener intencionalmente a miembros de la comunidad educativa.</p>
<p>• Suministrar información incorrecta a docentes o directivos.</p>
</ul>

<p><h1>PROTOCOLO DE ATENCIÓN:</p></h1>
<ul>
<p>• Reunión con las partes involucradas en el conflicto.</p>
<p>• Charlas de orientación con la(s) implicada(s) por parte del docente observador.</p>
<p>• Charlas con el director de grupo.</p>
<p>• Estrategias para reparar los daños causados y restablecer los derechos.</p>
<p>• Fijar una solución imparcial y justa con constancia escrita.</p>
<p>• Seguimiento y acompañamiento.</p>
<p>• Si es necesario, remisión al UCIC.</p>
</ul>

<p></h1>SITUACIONES TIPO II</p></h1>
<ul>
<p>• No es la primera vez que se presenta la situación.</p>
<p>• Acoso escolar o bullying.</p>
<p>• Ciberacoso escolar o ciberbullying.</p>
<p>• Agresión física con contenido sexual.</p>
<p>• Agresión física entre compañeros.</p>
<p>• Agresión verbal a directivos, docentes y estudiantes.</p>
</ul>
<p><h1>PROTOCOLO DE ATENCIÓN:</p></h1>
<ul>
<p>• Recolección de información a través de entrevistas.</p>
<p>• Remisión inmediata a entidad de salud en caso de daño físico.</p>
<p>• Notificación a los padres de todas las personas involucradas.</p>
<p>• Determinación de acciones para reparar los daños.</p>
<p>• Remisión al director de grupo, docente orientadora y Comité de Convivencia.</p>
<p>• Reporte en el Sistema de Información Unificado de Convivencia Escolar (SIUCE).</p>
<p>• Vinculación al proceso UCIC.</p>
</ul>
<p><h1>SITUACIONES TIPO III</p></h1>
<ul>
<p>• Homicidio.</p>
<p>• Acoso sexual.</p>
<p>• Consumo, venta o distribución de sustancias ilícitas.</p>
<p>• Presentarse bajo efectos de alcohol o drogas.</p>
<p>• Actos violentos o delictivos dentro o fuera de la institución.</p>
<p>• Pandillismo y grupos delictivos.</p>
<p>• Pornografía infantil.</p>
<p>• Extorsión.</p>
<p>• Falsificación de documentos o suplantación.</p>
<p>• Actos que atenten contra la dignidad, honra o vida de cualquier persona de la comunidad educativa.</p>
</ul>
<p><h1>PROTOCOLO DE ATENCIÓN:</p></h1>
<ul>
<p>• Reunión con las partes involucradas.</p>
<p>• Charlas de orientación con los implicados por parte del docente y el director de grupo.</p>
<p>• Estrategias de reconciliación y reparación de daños.</p>
<p>• Fijación de una solución justa y equitativa con constancia escrita.</p>
<p>• Remisión al UCIC y registro del caso en SIUCE.</p>
</ul>
<p><h1>RUTA Y PROTOCOLOS A SEGUIR</p></h1>
<ul>
<p>• De acuerdo a la Ley 1620 de 2013 y el Decreto 1965 de 2013, se proponen los siguientes pasos:</p>
<p>• Documentación y recolección de información.</p>
<p>• Entrevistas con las personas afectadas e implicadas.</p>
<p>• Atención inmediata a las personas involucradas.</p>
<p>• Reunión con docentes asignados y levantamiento de acta.</p>
<p>• Intervención con las partes involucradas para exponer sus puntos de vista.</p>
<p>• Convocatoria a padres de familia.</p>
<p>• Espacios para exposición de puntos de vista.</p>
<p>• Estrategias de reparación en caso de bullying.</p>
<p>• Remisión a psicología o Comité de Convivencia según el caso.</p>
<p>• Remisión a profesionales externos si es necesario.</p>
</ul>

<p></p>

<li><a href="#">Menú</a></li>

<h1 id="capitulo-XIII">Estrategias Convivenciales</h1>
<ul>
<p>CAPITULO XIII</p>
</ul>
<p>Estrategia – UCIC (Unidad de Cuidados Intensivos en Convivencia)</p>
<ul>
<p>Referentes Conceptuales:</p>
<p>• LEY 1620 DEL 15 DE MARZO DE 2013, POR LA CUAL SE CREA EL SISTEMA NACIONAL DE CONVIVENCIA ESCOLAR Y FORMACIÓN PARA EL EJERCICIO DE LOS DERECHOS HUMANOS, LA EDUCACIÓN PARA LA SEXUALIDAD Y LA PREVENCIÓN Y MITIGACIÓN DE LA VIOLENCIA ESCOLAR (ART 4-2,5; 13-1,4,5)</p>
<p>• DECRETO 1965 DEL 11 DE SEPTIEMBRE DE 2013, POR EL CUAL SE REGLAMENTA LA LEY 1620 DE 2013, (ART. 22; 29:1-5; ART.39; 41;42)</p>
<p>• Misión y Visión de la Institución Educativa Santa Teresita</p>
</ul>

<p>¿Qué es la UCIC?</p>
<ul>
<p>• No es un espacio físico, sino un estado del individuo que se somete a una revisión de sus actos, considerados como necesitados de cuidados intensivos para restablecer la convivencia.</p>
</ul>

<p>¿Cómo surge la UCIC?</p>
<ul>
<p>• La UCIC surge en respuesta a conflictos y agresiones escolares que requieren un manejo intensivo, como:</p>
<p>• Peleas entre pares</p>
<p>• Sustracción de objetos personales</p>
<p>• Acoso y ciberacoso escolar</p>
<p>• Uso de insultos, burlas y agresiones físicas o verbales</p>
<p>• Indisciplina reiterada</p>
</ul>
<p>¿Quiénes intervienen?</p>
<ul>
<p>• Docentes o directivos que conocieron el hecho</p>
<p>• Las partes en conflicto</p>
<p>• Familias de las estudiantes involucradas</p>
<p>• Coordinadora de la jornada</p>
<p>• Psicoorientadora</p>
<p>• Rector</p>

<p>Metodología</p>
<ul>
<p>Antes del proceso</p>

<p>• Recopilación de versiones de los hechos por las partes involucradas.</p>
<p>• Encuentro con las familias para analizar los hechos.</p>
<p>• Se informa a la familia que la estudiante entra en proceso UCIC, con suspensión académica según la evolución.</p>
</ul>
<p>Durante el proceso</p>
<ul>
<p>Primera Fase: Introspección</p>

<p>• Descripción del conflicto por la estudiante.</p>
<p>• Identificación de errores cometidos.</p>
<p>• Análisis de sentimientos asociados al conflicto.</p>
<p>• Propuestas iniciales para solucionar el conflicto.</p>
</ul>
<p>Segunda Fase: Proceso pedagógico</p>
<ul>
<p>• Lectura sobre el tema infringido.</p>
<p>• Desarrollo de talleres y conversatorios para interiorización de los temas.</p>
</ul>
<p>Tercera Fase: Evaluación y compromisos</p>
<ul>
<p>• Reconocimiento de los aprendizajes alcanzados.</p>
<p>• Establecimiento de compromisos de cambio de actitud.</p>
</ul>
<p>Después del proceso</p>
<ul>
<p>Cuarta Fase: Socialización y reconciliación</p>
<ul>
<p>• Socialización de lo aprendido con las compañeras.</p>
<p>• Disculpas y reconciliación con las partes involucradas.</p>
</ul>
<p>Quinta Fase: Monitoreo y seguimiento</p>
<ul>
<p>• Monitoreo semanal del cumplimiento del compromiso de la estudiante.</p>
<p>• Archivar la carpeta con los registros de todo el proceso.</p>
</ul>
<p>Sexta Fase: Vinculación de la familia</p>
<ul>
<p>• Presentación del proceso y aprendizajes a la familia.</p>
<p>• Matrícula de Observación</p>
<p>• Si la estudiante presenta dificultades reiteradas en su formación académica y en la convivencia, se establece matrícula en observación para el año lectivo, involucrando a la familia en el proceso.</p>
<p>• SIUCE (Sistema de Información Unificado de Convivencia Escolar)</p>
<p>• Plan de acción para el registro y seguimiento de casos de violencia escolar, con el objetivo de proteger los derechos de los estudiantes:</p>
<p>• Sensibilización y capacitación a la comunidad educativa sobre el SIUCE.</p>
<p>• Implementación del sistema y formación de equipos interdisciplinarios para su uso.</p>
<p>• Registro y seguimiento de casos en la plataforma SIUCE.</p>
<p>• Promoción de una cultura de paz y articulación con autoridades locales.</p>
</ul>
<li><a href="#">Menú</a></li>
</main>

    <script>
        document.addEventListener("DOMContentLoaded", () => {
            const navItems = document.querySelectorAll("nav ul > li");

            navItems.forEach(item => {
                item.addEventListener("click", () => {
                    // Cerrar todos los submenús primero
                    navItems.forEach(i => i.classList.remove("active"));

                    // Abrir solo el submenú del elemento actual
                    item.classList.add("active");
                });
            });

            // Cerrar submenú al hacer clic en cualquier enlace dentro del submenú
            const subMenuLinks = document.querySelectorAll("nav ul li ul li a");
            subMenuLinks.forEach(link => {
                link.addEventListener("click", () => {
                    navItems.forEach(item => item.classList.remove("active"));
                });
            });

            // Opcional: Ocultar menú cuando se haga clic fuera del mismo
            document.addEventListener("click", (e) => {
                if (!e.target.closest("nav")) {
                    navItems.forEach(item => item.classList.remove("active"));
                }
            });
        });
    </script>
</body>
</html>

    <footer>
        <p>© 2024 Institución Educativa Santa Teresita. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
