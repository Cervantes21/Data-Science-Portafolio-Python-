<div style="background-color:#edae49;color:#d1495b;font-family:monospace;text-align:center;padding-top:20px;font-size:22px;">
    <h1><b>Cyclistic Bike sharing</b></h1>
    <figure style='display:inline-block'>
        <img style='width:350px;height:350px;border-radius:175px;box-shadow: 15px 15px 15px #423e37;'src='https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWw4ano0cndyeHdueGt2dWVvbmwxNG1ibGhhODc2amN0dXFoZDNuZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/kAnpk0N9Ph3he/giphy.gif'>
    </figure>
    <footer><h3 style='font-size:18pxi;padding-bottom:20px' align='right'>Por: <b>Andrés Cervantes</b></h3></footer>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:18px;padding-left:7px;padding-top:9px">
    <h2><b>Acerca de Cyclistic:</b></h2>
    <p>
        En 2016, Cyclistic lanzó una exitosa oferta de bicicletas compartidas. Desde entonces, el programa creció hasta alcanzar <b>una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en toda Chicago</b>. Las bicicletas se pueden desbloquear desde una estación y devolverse en cualquier otra estación del sistema en cualquier momento.<br>
<p>Hasta ahora, la estrategia de marketing de Cyclistic se basaba en la construcción de un reconocimiento de marca general y en atraer a amplios segmentos de consumidores.<br></p>
<p>Uno de los enfoques que ayudó a hacer esto posible fue la flexibilidad de sus <b>planes de precios: pases de un solo viaje, pases de un día completo y membresías anuales.</b><br></p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimg.chilango.com%2F2018%2F02%2Fbicicletas-cdmx-1.jpg&f=1&nofb=1&ipt=7230d5fb4c7e9093ca1f056c7a9987badb6d2e74b8a3c2602e1411295c69f8ad&ipo=images' width=300 style='border-radius: 10px;'>
</div>
<p><b>A los clientes que compran pases de un solo viaje o pases de un día completo se los llama ciclistas ocasionales. Los clientes que compran membresías anuales se llaman miembros de Cyclistic.</b><br></p>
<div align='center'>
<img src='https://miro.medium.com/v2/resize:fit:600/1*knQ2PfM09kg7T3XDf3fQlQ.gif' width=200 style='border-radius: 20px;'>
</div>
<p>Los analistas financieros de Cyclistic llegaron a la conclusión de que los miembros anuales son mucho más rentables que los ciclistas ocasionales.<br></p>
<p>Aunque la flexibilidad de precios ayuda a Cyclistic a atraer más clientes, <b>Moreno cree que maximizar el número de miembros anuales será clave para el crecimiento futuro.</b> En lugar de crear una campaña de marketing que apunte a todos los clientes nuevos, Moreno cree que hay muchas posibilidades de convertir a los ciclistas ocasionales en miembros.<br></p>
<p><b>Ella señala que los ciclistas ocasionales ya conocen el programa de Cyclistic y han elegido a Cyclistic para sus necesidades de movilidad</b>.<br></p>
<p>Moreno estableció una meta clara: <b>Diseñar estrategias de marketing orientadas a convertir a los ciclistas ocasionales en miembros anuales.</b><br></p>
<div align='center'>
<img src='https://cdn.pixabay.com/photo/2013/07/13/01/10/sprint-155240_960_720.png' width=400>
</div>
<p>Sin embargo, para hacer eso, el equipo de analistas de marketing necesita entender mejor cómo difieren los miembros anuales y los ciclistas ocasionales, <b>por qué los ciclistas ocasionales comprarían una membresía y cómo los medios digitales podrían afectar sus tácticas de marketing.</b> Moreno y su equipo están interesados en analizar los datos históricos de viajes en bicicleta de Cyclistic para <b>identificar tendencias</b>.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fskyje.com%2Fwp-content%2Fuploads%2F2018%2F08%2Fanalytics-solutions.jpg&f=1&nofb=1&ipt=b6a6e531c574e6a0c024ac637f9ec70221ab3d44ff22b6fe4ab7a311dcc4d85a&ipo=images' width=400 style='border-radius: 10px;'>
</div>
</p>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;padding-top:9px;font-size:20px;padding-left:7px;">
<h1 id="introducci%C3%B3n"><strong>Introducción</strong></h1>
<blockquote>
<p>Para este caso mencionó que sólo es un proyecto de una empresa ficticia. El proposito de este Notebook es practicar y usar las herramientas aprendidas para el Caso práctico No.1 de <a href="https://www.coursera.org/learn/completa-un-caso-practico/home/week/2"><strong>Google Data Analytics Professional</strong></a></p>
</blockquote>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flogos-world.net%2Fwp-content%2Fuploads%2F2020%2F09%2FGoogle-Logo.png&f=1&nofb=1&ipt=7563622007acd9a3df7ed433b66bf1e285cd74017e6082cfaed2edb8fd5609bf&ipo=images' width=200>
</div>
<blockquote>
<p>Así como la actualización para presentar lo aprendido en las carreras de <a href="https://platzi.com/ruta/data-engineer/?school=_escuela_datos_"><strong>Data Engineer</strong></a> y <a href="https://platzi.com/ruta/data-scientist-python/?school=_escuela_datos_"><strong>Data Scientist</strong></a></p>
</blockquote>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn-images-1.medium.com%2Fmax%2F1600%2F1*rrRcaZKZsjerUveQqTSx7A.png&f=1&nofb=1&ipt=aaa0a0450b8be78955b140ab478fc287093eabe6f3582b352ab2255ee0325b11&ipo=images' width=200 style='border-radius:10px;'>
</div>
<h2 id="escenario"><strong>Escenario:</strong></h2>
<p>La directora de marketing cree que el éxito futuro de la empresa depende de maximizar la cantidad de membresías anuales.</p>
<p>Por lo tanto, tu equipo quiere entender qué diferencias existen en el uso de las bicicletas Cyclistic entre <strong>los ciclistas ocasionales</strong> y <strong>los miembros anuales</strong>.</p>
<p>A través de estos conocimientos, tu equipo diseñará una nueva estrategia de marketing para convertir a los ciclistas ocasionales en miembros anuales.</p>
<p>Sin embargo, antes de eso, los ejecutivos de Cyclistic deben aprobar tus recomendaciones; por eso, debes respaldar tu propuesta con una visión convincente de los datos y visualizaciones profesionales de los mismos.</p>
<h2 id="las-preguntas"><strong>Las preguntas:</strong></h2>
<p>Tres preguntas guiarán el futuro programa de marketing:</p>
<ol>
<li>¿En qué se diferencian los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?</li>
<li>¿Por qué los ciclistas ocasionales comprarían membresías anuales de Cyclistic?</li>
<li>¿Cómo puede usar Cyclistic los medios digitales para influenciar a los ciclistas ocasionales a convertirse en miembros?</li>
</ol>
<h2 id="instrucci%C3%B3n-clara-de-la-tarea-empresarial"><strong>Instrucción clara de la tarea empresarial:</strong></h2>
<p>El objetivo es identificar las diferencias en el empleo de las bicicletas de Cyclistic entre <strong>los miembros anuales</strong> y <strong>los ciclistas ocasionales</strong>. El análisis de los datos históricos de viajes en bicicleta de Cyclistic permitirá determinar patrones y tendencias de uso que puedan ayudar a diseñar una estrategia de marketing efectiva para convertir a ciclistas ocasionales en miembros anuales.</p>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:18px;padding-top:7px;padding-left:9px;">
<h2 id="metodolog%C3%ADa"><strong>Metodología:</strong></h2>
<p>Para esta práctica utilizaremos la metodología de:</p>
<ul>
<li><strong>Preparar</strong>: Usaremos los datos históricos de los viajes de <strong>Cyclistic</strong> para analizar e identificar tendencias. Pero primero Descargaremos los últimos 12 meses de viajes del conjunto de datos</li>
<li><strong>Procesar</strong>: Comenzaremos con la organización y la limpieza de los datos, así como la imputación de ser requerido para dar paso a comenzar a explorar nuestros datos.</li>
<li><strong>Analizar</strong>: Haremos un análisis exploratorio de datos (<strong>EDA</strong>) Para poder comprender nuestro conjunto de datos, a través de la visualización de datos y posteriormente crearemos modelos de machine learning para ir respondiendo nuestras preguntas a cerca de los datos y nuestra <strong>Tarea Empresarial</strong></li>
<li><strong>Compartir</strong>: En esta sección compartiremos nuestros resultados con los interesados, además de contestar claramente nuestras preguntas. Esta parte de la metodología se estará usando a lo largo de la lectura, para ir comprendiendo tanto el análisis, como los resultados.</li>
</ul>
<h2 id="herramientas"><strong>Herramientas</strong>:</h2>
<p>Para esta práctica he optado por utilizar <strong>Python</strong>, ya que va a ser una excelente herramienta que supla la necesidad de usar más herramientas como <strong>EXCEL</strong>, con la cual por medio de librerías podemos descargar, manipular, editar y visualizar nuestros datos.</p>
<div align='center'>
<img src='https://miro.medium.com/v2/resize:fit:679/1*IRGB-4OAoO8KSqH_huDPFw.gif' width=400 style='border-radius: 20px;'>
</div>
<p>También he optado por <strong>Kaggle</strong> como forma de compartir mi proyecto, porque permite almacenar nuestro conjunto de datos y al mismo tiempo nos brinda una cómoda visualización de nuestro Notebook.</p>
<p><a href="https://www.kaggle.com/code/andydollin21/case-study-cyclistic"><strong>Kaggle</strong></a></p>
<p>Así mismo, usaré herramientas como <strong>Pyspark</strong> como manejador de datos, comandos con <strong>bash</strong> y guardaremos nuestros resultados en un repositorio de <strong>GitHub</strong> y nuestra versión en <strong>Kaggle</strong></p>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;padding-top:9px;font-size:20px;padding-left:7px;">
<p><a href="https://divvy-tripdata.s3.amazonaws.com/index.html">Descarga los últimos 12 meses de datos de viajes de Cyclistic. aquí</a>.</p>
<p>(Nota: Los conjuntos de datos tienen un nombre diferente porque Cyclistic es una empresa ficticia. A los fines de este caso práctico, los conjuntos de datos son apropiados y nos permitirán responder las preguntas de la empresa. Los datos han sido proporcionados por <a href="https://motivateco.com/"><strong>Motivate International Inc</strong></a>. bajo esta (<a href="https://ride.divvybikes.com/data-license-agreement">licencia</a>.)</p>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;text-align:center;font-size:14px;">
<h2 id="explicaci%C3%B3n-del-conjunto-de-datos"><strong>Explicación del conjunto de datos</strong>:</h2>
<p>Explicaré las variables de nuestras columnas.</p>
<table>
<thead>
<tr>
<th><strong>Nombre</strong></th>
<th><strong>Descripción</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>ride_id</strong></td>
<td>identificador único del viaje.</td>
</tr>
<tr>
<td><strong>rideable_type</strong></td>
<td>tipo de bicicleta usada en el viaje.</td>
</tr>
<tr>
<td><strong>started_at</strong></td>
<td>fecha y hora de inicio del viaje.</td>
</tr>
<tr>
<td><strong>ended_at</strong></td>
<td>fecha y hora de fin del viaje.</td>
</tr>
<tr>
<td><strong>start_station_name</strong></td>
<td>nombre de la estación de inicio del viaje.</td>
</tr>
<tr>
<td><strong>start_station_id</strong></td>
<td>identificador único de la estación de inicio del viaje.</td>
</tr>
<tr>
<td><strong>end_station_name</strong></td>
<td>nombre de la estación de fin del viaje.</td>
</tr>
<tr>
<td><strong>end_station_id</strong></td>
<td>identificador único de la estación de fin del viaje.</td>
</tr>
<tr>
<td><strong>start_lat</strong></td>
<td>latitud de la estación de inicio del viaje.</td>
</tr>
<tr>
<td><strong>start_lng</strong></td>
<td>longitud de la estación de inicio del viaje.</td>
</tr>
<tr>
<td><strong>end_lat</strong></td>
<td>latitud de la estación de fin del viaje.</td>
</tr>
<tr>
<td><strong>end_lng</strong></td>
<td>longitud de la estación de fin del viaje.</td>
</tr>
<tr>
<td><strong>member_casual</strong></td>
<td>tipo de usuario que realizó el viaje (miembro anual o usuario ocasional).</td>
</tr>
</tbody>
</table>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;text-align:center;font-size:22px;">
<h1 id="compartir-resumen-y-conclusiones"><strong>COMPARTIR</strong>: Resumen y conclusiones</h1>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;text-align:center;font-size:20px;">
<h2 id="introducci%C3%B3n"><strong>Introducción:</strong></h2>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Las bicicletas son una excelente opción para movernos por las ciudades porque son amigables con el medio ambiente, te ponen en forma y te ahorran tiempo en el tráfico.</p>
<p>Pedaleando, no emites gases contaminantes y contribuyes a tener aire más limpio.</p>
<p>Pero lo mejor es que ahora hay empresas que te permiten alquilar bicicletas fácilmente. No necesitas tener una propia, solo alquilas una cuando la necesitas.</p>
<p>Esto es genial porque fomenta el uso compartido, lo que es más sostenible y ahorra espacio en la ciudad.</p>
<p>Estas compañías están ayudando a que el ciclismo sea más accesible y cómodo para todos, y eso es fabuloso para el ambiente y para nosotros.</p>
<p>Por ello hablaremos un poco acerca de una empresa que esta haciendo algo prometedor, y es <strong>Cyclistic</strong>.</p>
<p>Primero que nada debemos recordar que viene haciendo la empresa, como sabemos <strong>Cyclistic</strong> tiene una una <strong>flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en toda Chicago</strong></p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Frealestatemarket.com.mx%2Fimages%2F2019%2F01-Enero%2F1101%2F1101g-movilidad-cdmx.jpg&f=1&nofb=1&ipt=3f0a92518c836bf42c19fdca40b79351f0c4b3a6bc3245f0922001af84ee668a&ipo=images' width=400 style='border-radius: 10px;'>
</div>
<p><strong>Esto quiere decir que las bicicletas son las que nos proporcionan todos los datos del conjunto, ya que están siendo monitoreadas constantemente.</strong></p>
<div align='center'>
<img src='https://ciudadessegurasyconfiables.com/wp-content/uploads/2022/07/lock11.gif' width=300>
</div>
<p>Además que cuenta con una una red muy amplia, comparandola con una empresa en México llamada <a href="https://ecobici.cdmx.gob.mx/"><strong>Ecobici</strong></a>.</p>
<div align='center'>
<img src='https://cuentometro.files.wordpress.com/2020/10/imagendestacada-2.jpg' width=400 style='border-radius: 10px;'>
</div>
<blockquote>
<p>Actualmente hay bastantes empresas que se dedican a rentar bicicletas con el fin de mejorar la vialidad en la <strong>Ciudad de México</strong>, tal es el caso de la pionera <a href="https://ecobici.cdmx.gob.mx/"><strong>Ecobici</strong></a>, la cual brinda este servicio desde el <strong>año 2010</strong> cuando comenzó con tal sólo <strong>85 cicloestaciones</strong> distribuidas en una sola alcaldía y <strong>1,200 bicicletas</strong>.
A medida que el tiempo pasó y la gente se interesó por el servicio, han crecido de manera exponencial, pues al día de hoy cuentan con más de <strong>7 mil bicicletas y 480 estaciones</strong>.</p>
</blockquote>
<ul>
<li><strong>Fuente</strong>: <a href="https://cuentometer.com/2020/10/12/sabes-cuantas-bicis-se-rentan-en-la-cdmx/"><strong>Cuentometro</strong></a></li>
</ul>
<p>Estos datos son importantes, ya que la población de <strong>Ciudad de México</strong> cuenta con más de <strong>9.2 millones</strong> de habitantes, contra <strong>2.7 millones</strong> de habitantes en <strong>Chicago</strong>.</p>
<ul>
<li><strong>Fuentes</strong>: <a href="https://es.wikipedia.org/wiki/Chicago"><strong>Wikipedia</strong></a>, <a href="http://www.cuentame.inegi.org.mx/monografias/informacion/df/poblacion/"><strong>INEGI</strong></a></li>
</ul>
<p>Así que <strong>Cyclistic</strong> claramente lleva una delantera con su estrategía de crecimiento, aunque cuenta con menos bicicletas con una diferencia aproximada de <strong>2 mil bicicletas</strong>, la ventaja que tiene <strong>Cyclistic</strong> a su favor, es que cuenta con <strong>más estaciones</strong>.</p>
<p>Además podemos suponer que bajo estás cifras, <strong>Ecobici</strong> toma aproximadamente el <strong>13%</strong> del mercado con su capacidad total, mientras que <strong>Cyclistic</strong>, presenta un optimo crecimiento con el <strong>5%</strong>.</p>
<p>Dentro de esta investigación, los comentarios de los usuarios de <strong>Ecobici</strong>, argumentan una necesidad por más estaciones.</p>
<div align='center'>
<img src='https://f.hubspotusercontent10.net/hubfs/2621212/052021_blog.gif' width=400 style='border-radius: 10px;'>
</div>
<ul>
<li><strong>Fuente</strong>: <a href="https://www.clarin.com/ciudades/usuarios-quejan-eliminacion-20-estaciones-ecobici_0_kOnwHxXL.html">El clarin</a></li>
</ul>
<p>La diferencia en este caso desarrolla un impacto negativo, tanto en la experiencia al usuario, como una mala imagen hacia la empresa;
Siendo por más de <strong>200 estaciones en uso</strong>, la diferencia entre  <strong>Cyclistic</strong> y <strong>Ecobici</strong>.</p>
<p>Pero no todo es malo, y más adelante mencionaremos algunos detalles al respecto.</p>
<hr>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Retomando, acerca de <strong>Cyclistic</strong>, la estrategia de marketing, se basaba en la construcción de un reconocimiento de marca general y en atraer a amplios segmentos de consumidores.</p>
<p>Uno de los enfoques que ayudó a hacer esto posible fue la flexibilidad de sus planes de precios:</p>
<ul>
<li><strong>Pases de un solo viaje</strong></li>
<li><strong>Pases de un día completo</strong></li>
<li><strong>Membresías anuales.</strong></li>
</ul>
<p>Recordemos que a los clientes que compran pases de un solo viaje o pases de un día completo se los llama <strong>ciclistas ocasionales</strong>.</p>
<p>Mientras que los clientes que compran membresías anuales se llaman <strong>miembros de Cyclistic</strong>.</p>
<p>Todo esto les ha traido grandes ventajas y hasta ahora la campaña de <strong>marketing</strong> enfocada al crecimiento se ha adaptado bastante bien, de tal modo que podemos observar en la siguiente gráfica la distribución de los tipos de <strong>usuarios</strong> que tenemos:</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/01_usuarios_por_tipo.png?raw=true' width=600 style='border-radius: 10px;'>
</div>
<p>En esta gráfica vemos que tenemos <strong>2,322,032 (2 millones, 322 mil, 032)</strong> de <strong>ciclistas ocacionales</strong>, mientras que de <strong>miembros anuales</strong> contamos con <strong>3,345,685 (3 millones, 345 mil, 685)</strong> esta cifra corresponde al total adquirido hasta el año 2022 y tenemos un total de <strong>5,667,717 (5 millones, 667 mil, 717)</strong> de usuarios.</p>
<p>Ahora, nuestro objetivo, es poder crecer aún más los <strong>miembros anuales</strong>, y sabemos que la estrategía de marketing que se quiere implementar ahora, es buscar &quot;fidelizar&quot;, o &quot;convertir&quot; a esos <strong>ciclistas ocacionales</strong> en nuevos <strong>miembros de Cyclistic</strong></p>
<div align='center'>
<img src='https://expandeonline.cl/wp-content/uploads/2020/03/cliente-feliz-EO-452x325.png' width=300>
</div>
<p>Para ello, pasemos a la primer pregunta:</p>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;text-align:center;font-size:18px;">
<h3 id="1-%C2%BFcu%C3%A1l-es-la-diferencia-entre-los-socios-anuales-y-los-ciclistas-ocasionales-con-respecto-al-uso-de-las-bicicletas-de-cyclistic"><strong>1. ¿Cuál es la diferencia entre los socios anuales y los ciclistas ocasionales con respecto al uso de las bicicletas de Cyclistic?</strong></h3>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Antes de sumergirnos en los datos, es importante comprender la relevancia de las bicicletas como una solución para los desafíos urbanos que enfrentamos.</p>
<p>Las bicicletas juegan un papel crucial en la lucha contra la congestión vial y la contaminación en nuestras ciudades.</p>
<div align='center'>
<img src='https://assets.sutori.com/user-uploads/image/7748c8c3-061a-4853-86ad-e4358a986e13/e0a7c638f27d5812d81fd3f8fe77284f.gif' width=300 style='border-radius: 10px;'>
</div>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Al elegir pedalear, contribuimos activamente a reducir las emisiones de carbono y a mejorar la calidad del aire. Además, montar en bicicleta nos brinda la oportunidad de mantenernos en forma y llevar un estilo de vida más saludable.</p>
<div align='center'>
<img src='https://media.tenor.com/aXSrb0ow1AAAAAAC/bicycle-student.gif' width=200 style='border-radius: 10px;'>
</div>
<p>Otro aspecto clave es su capacidad para sortear el tráfico y ahorrar tiempo en los desplazamientos urbanos. Las bicicletas son ágiles y flexibles, lo que nos permite movernos de manera eficiente por el tráfico de la ciudad.</p>
<div align='center'>
<img src='https://img.freepik.com/vector-gratis/ilustracion-concepto-estacionamiento-bicicletas_114360-13517.jpg?w=360' width=300 style='border-radius: 10px;'>
</div>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Las empresas de renting de bicicletas también han desempeñado un papel importante en el fomento del uso de este medio de transporte.</p>
<p>Estas compañías proporcionan acceso fácil y flexible a bicicletas sin la necesidad de ser propietario de una.</p>
<p>Los sistemas de alquiler de bicicletas ofrecen a los ciudadanos una opción de movilidad adicional que complementa el transporte público y les brinda una alternativa eficiente y económica para sus desplazamientos diarios.</p>
<p>Empresas como <strong>Cyclistic</strong>, que ofrecen servicios de renting de bicicletas, impulsan la economía compartida y contribuyen a optimizar el uso del espacio urbano.</p>
<p><strong>¿Cómo?</strong></p>
<p>Además del beneficio individual para los usuarios, el enfoque compartido de las empresas de alquiler de bicicletas tiene un impacto positivo en la comunidad y el medio ambiente. La economía compartida fomenta el uso más eficiente de recursos al aprovechar una flota de bicicletas en lugar de que cada individuo posea su propio vehículo. Esto resulta en una reducción de la demanda de estacionamientos y, en consecuencia, en un uso más eficiente del espacio urbano.</p>
<p>Así que, en general, están ayudando a crear ciudades más amigables con el medio ambiente y más cómodas para sus habitantes.</p>
<div align='center'>
<img src='https://www.capital21.cdmx.gob.mx/noticias/wp-content/uploads/2023/02/Ciclovias-CDMX-01.jpg' width=300 style='border-radius: 10px;'>
</div>
</div>
<ul>
<li><a href="https://sobredosruedasempresariales.weebly.com/bici-informate.html"><strong>Fuente</strong></a></li>
</ul>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Su enfoque en convertir a ciclistas ocasionales en miembros comprometidos es fundamental para garantizar un crecimiento sostenible para la empresa.</p>
<p>por ello vamos a explorar cual es el comportamiento de los usuarios, con respecto al conjunto de datos proporcionado y descubramos cómo <strong>Cyclistic</strong> está liderando esta transformación.</p>
<div align='center'>
<img src='https://static.vecteezy.com/system/resources/previews/008/985/403/non_2x/concept-customer-and-operator-online-technical-support-24-7-for-web-page-male-hotline-operator-advises-client-online-assistant-virtual-help-service-for-business-vector.jpg
' width=400 style='border-radius: 20px;'>
</div>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Comenzamos nuestra exploración con una gráfica que muestra la duración promedio de los viajes entre los ciclistas ocasionales y los miembros anuales.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/02_duracion_promedio_viaje.png?raw=true' width=600 style='border-radius:10px;'>
</div>
<p>Apoyado a esto, creamos una gráfica con <strong>Machine learning</strong> que nos dios predicciones sobre el comportamiento de los usuarios, con respecto a la duración:</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/15_duracion_promedio_del_viaje_por_usuario.jpg?raw=true' width=600 style='border-radius:10px;'>
</div>
<hr>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Es interesante observar las diferencias en la duración promedio de los viajes entre los ciclistas ocasionales y los miembros anuales. Aparentemente, los <strong>ciclistas ocasionales</strong> tienden a realizar viajes más largos, con una duración promedio de <strong>29 minutos</strong>, mientras que los <strong>miembros anuales</strong> tienen viajes más cortos, con una duración promedio de <strong>12 minutos</strong>.</p>
<p>Esto podría deberse a que los <strong>miembros anuales</strong> utilizan las bicicletas con mayor frecuencia y para trayectos más cortos, como desplazamientos diarios o recorridos locales.</p>
<div align='center'>
<img src='https://www.eleconomista.com.mx/__export/1644458410672/sites/eleconomista/img/2022/02/09/ciclismo-urbano-cdmx-gilberto-marquina_1.png_1014274486.png' width=400>
</div>
<p>Y por otro lado los <strong>ciclistas ocasionales</strong> lo utilizan más como un medio recreativo.</p>
<div align='center'>
<img src='https://www.lavanguardia.com/files/content_image_mobile_filter/uploads/2020/07/08/5fa919aff2683.jpeg' width=400>
</div>
<hr>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Apoyado esto, también tenemos la gráfica que nos resultó con machine learning, en dónde podemos observar que los <strong>ciclistas ocasionales</strong> van a una tendencia los días <strong>Sábados</strong>, mientras que los <strong>miembros anuales</strong> tienen una tendencia hacia los días <strong>Miércoles</strong></p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/17_clustering_of_hours_and_duration.jpg?raw=true' width=600 style='border-radius: 10px;'>
</div>
<p>Los <strong>Miércoles</strong> muestran una mayor actividad entre los <strong>miembros anuales</strong>, lo que podría indicar que utilizan las bicicletas de manera más habitual durante los días laborables.</p>
<p>Por otro lado, los <strong>Sábados son los días con mayor actividad entre los ciclistas ocasionales</strong>, lo que podría deberse a que aprovechan el fin de semana para realizar recorridos más extensos o actividades recreativas.</p>
<p>Entonces el resultado de nuestros datos apoya que los <strong>miembros anuales</strong> utilizan los servicios de <strong>Cyclistic</strong> más como un método de transportación alternativa. Mientras que los <strong>ciclistas ocasionales</strong> buscan el lado recreativo del ciclismo.</p>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Ahora, pasemos a analizar cuáles son las similitudes que presentan, entre ellos.</p>
<p>En esta gráfica, examinaremos el uso de bicicletas por cada usuario individualmente.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/10_uso_de_bicicletas_por_usuario.png?raw=true' width=600 style='border-radius: 10px;'>
</div>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>La preferencia por las <strong>bicicletas clásicas</strong> es compartida por ambos grupos de usuarios, lo que sugiere que estas bicicletas tradicionales son cómodas y adecuadas para la mayoría de los desplazamientos urbanos.</p>
<div align='center'>
<img src='https://i.imgur.com/HW2rBMi.gif' width=400 style='border-radius: 20px;'>
</div>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Sin embargo, es relevante notar <strong>la tendencia al alza en el uso de bicicletas eléctricas</strong>. Esto podría ser indicativo de un mayor interés por parte de los usuarios en obtener una asistencia adicional en sus desplazamientos, lo que les permite realizar viajes más largos o superar pendientes con mayor facilidad.</p>
<div align='center'>
<img src='https://i.pinimg.com/originals/6b/0e/e1/6b0ee15edaf92743efe7ad6e75059cb8.gif
' width=400 style='border-radius: 20px;'>
</div>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Además, otra similitud que arrojan los datos es el día más frecuente para todos los usuarios:</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/05_duracion_prom_porDia_yHora.png?raw=true' width=600 style='border-radius: 10px;'>
</div>
<p>El hecho de que los <strong>Viernes</strong> sean el día más popular para el uso de bicicletas de <strong>Cyclistic</strong> representa una oportunidad valiosa para la empresa. Podrían considerar estrategias de promoción específicas para este día, como ofertas especiales, eventos o actividades para atraer aún más usuarios y fomentar el uso de bicicletas como una alternativa sostenible y saludable para los desplazamientos urbanos.</p>
<hr>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Ahora, mencionemos un poco de lo que viene haciendo también <strong>Ecobici</strong> y dentro de su oferta no sólo ofrece una tarjeta, sino también una aplicación:</p>
<div align='center'>
<img src='https://ecobici.cdmx.gob.mx/wp-content/uploads/2022/08/costos-verde-1.png' width=300 style='border-radius: 20px;'>
</div>
<p>En resumen, está aplicación te permite escanear el código de la bicicleta y aplica la tarifa por medio de un plan, o una suscripción. Eso otorga muchas facilidades a sus usuarios para poder usar su servicio de manera más eficiente.</p>
<p>Pero también visto a nivel de <strong>Ciencia de datos</strong>, que tengan una aplicación hace que los atributos de su base de datos sea más robusta para poder analizar mejor a sus usuarios. Actualmente, <strong>Ecobici</strong> Tiene sus datos abiertos para uso estadístico abierto. Más adelante en otro proyecto se podría atender una comparativa más profunda.</p>
<ul>
<li><strong>Fuente:</strong> <a href="https://ecobici.cdmx.gob.mx/conoce-sistema/">Ecobici</a></li>
</ul>
<hr>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Ahora, retomando la tendencia de las <strong>bicicletas eléctricas</strong>, sabemos que están equipadas con un motor eléctrico que proporciona asistencia al pedaleo, lo que permite a los ciclistas superar pendientes o distancias más largas con mayor facilidad.</p>
<p>Esta tendencia sugiere que los usuarios de <strong>Cyclistic</strong> están buscando soluciones más eficientes y cómodas para sus desplazamientos. <strong>Las bicicletas eléctricas</strong> les ofrecen la posibilidad de realizar viajes más extensos sin tener que esforzarse tanto, lo que puede ser especialmente útil para aquellos que necesitan llegar a destinos más alejados o enfrentan terrenos más difíciles.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.excelsiorcalifornia.com%2Fwp-content%2Fuploads%2F2018%2F11%2FIMG_2509-1.jpg%3Fw%3D1024%26h%3D768&f=1&nofb=1&ipt=11262035a5cd282720a5a5a4b36d6ee0fb3ed4bef8f5275fd0ddc5cf2a3a71ea&ipo=images' width=300 style='border-radius:5px;'>
</div>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Para <strong>Cyclistic</strong>, esta tendencia puede ser un punto clave a considerar en su estrategia de expansión y oferta de servicios. A medida que la demanda de bicicletas eléctricas continúa creciendo, la empresa podría considerar aumentar su flota de bicicletas eléctricas y expandir su red de estaciones para satisfacer las necesidades de los usuarios y seguir liderando el camino hacia una movilidad más ecológica en Chicago.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages-na.ssl-images-amazon.com%2Fimages%2FI%2F71tvOhVGjgL._AC_SL1500_.jpg&f=1&nofb=1&ipt=6cb4950b0e8e68b8ede65dca28c5d107735e528920147f2c41c7601c96dbc65f&ipo=images' width=300 style='border-radius:5px;'>
</div>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Sabemos ahora, que los usuarios prefieren las <strong>bicicletas tradicionales</strong>, pero tenemos una inclinación por <strong>bicicletas eléctricas</strong>, además, sabemos que el día preferido de los usuarios es el día <strong>Viernes</strong>. Pero, no sólo eso, la siguiente gráfica nos mostrará las horas recurrentes del día en las que los usuarios de <strong>Cyclistic</strong> prefieren utilizar las bicicletas.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/03_hora_recurrente.png?raw=true' width=700 style='border-radius:10px;'>
</div>
<p>la gráfica revela que las <strong>17 horas (5:00 PM)</strong> son las horas más recurrentes para todos los usuarios.</p>
<p>Esta hora parece ser el punto óptimo en el que los usuarios encuentran conveniente y placentero utilizar las bicicletas.</p>
<hr>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>¿Qué podría explicar esta tendencia hacia las 05:00 PM?</p>
<p>Algunas posibles razones podrían ser:</p>
<ul>
<li>
<p><strong>Fin de la jornada laboral</strong>: A las 17 horas, muchas personas han finalizado su jornada laboral y pueden optar por utilizar las bicicletas como medio de transporte para regresar a casa o realizar actividades recreativas.</p>
</li>
<li>
<p><strong>Hora de ocio</strong>: A esta hora, los usuarios pueden tener tiempo libre para disfrutar de un paseo en bicicleta después del trabajo o como parte de su rutina de ocio.</p>
</li>
</ul>
<div align='center'>
<img src='https://bogota.gov.co/sites/default/files/inline-images/bici-051.gif' width=300>
</div>
<ul>
<li>
<p><strong>Menos tráfico</strong>: Las 17 horas pueden coincidir con un momento del día en el que hay menos tráfico en las calles, lo que hace que el uso de bicicletas sea más atractivo y cómodo.</p>
</li>
<li>
<p><strong>Condiciones climáticas</strong>: Dependiendo de la época del año, las 17 horas pueden ser una hora óptima en términos de clima, lo que puede influir en la elección de utilizar las bicicletas.</p>
</li>
</ul>
<div align='center'>
<img src='https://us.123rf.com/450wm/elvetica/elvetica1611/elvetica161100013/68424203-hombre-y-mujer-con-bicicleta-viajar-con-bicicleta-ilustraci%C3%B3n-de-vector-de-estilo-plano.jpg' width=300 style='border-radius:20px;'>
</div>
<hr>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Lo que nos lleva a la siguiente gráfica, donde analizaremos la distribución de usuarios a lo largo del año.</p>
<p>Veremos si hay meses con mayor actividad en el uso  entre los ciclistas ocasionales y los miembros anuales</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/04_usuarios_por_mes.png?raw=true' width=700 style='border-radius:10px;'>
</div>
<hr>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Los datos muestran claramente que tanto los miembros anuales como los ciclistas ocasionales tienen meses específicos en los que su actividad es más alta.</p>
<p>Para los <strong>miembros anuales</strong>, el mes más frecuente es <strong>agosto</strong>, con un impresionante <strong>total de 427,008 (427 mil, 008) usuarios</strong>. Esto podría deberse a varias razones:</p>
<ul>
<li>
<p><strong>Vacaciones de verano</strong>: <strong>Agosto</strong> es un mes en el que muchas personas toman vacaciones de verano, lo que podría llevar a un mayor uso de bicicletas para actividades recreativas y para explorar la ciudad durante las vacaciones.</p>
</li>
<li>
<p><strong>Clima favorable</strong>: En muchas ciudades, agosto es un mes de clima cálido y agradable, lo que puede motivar a más personas a utilizar bicicletas para sus desplazamientos diarios o para paseos al aire libre.</p>
</li>
</ul>
<div align='center'>
  <img src='https://i.gifer.com/origin/68/68118aaaeba4a87c51b0b1247df0a5d1.gif' width='300' style='border-radius: 20px;'>
</div>
<ul>
<li><strong>Eventos y festivales</strong>: Agosto puede ser un mes en el que hay eventos, festivales y actividades en la ciudad que atraen a más usuarios a utilizar las bicicletas como medio de transporte para llegar a estos eventos.</li>
</ul>
<div align='center'>
<img src='https://www.tribunadesanluis.com.mx/local/whslln-ciclista/ALTERNATES/LANDSCAPE_768/ciclista' width=300 style='border-radius:10px;'>
</div>
<hr>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>En cuanto a los <strong>ciclistas ocasionales</strong>, <strong>julio</strong> destaca como el mes más frecuente, con un total de <strong>406,055 (406 mil, cincuenta y cinco) usuarios</strong>. Algunas posibles razones para esta alta actividad podrían ser:</p>
<ul>
<li>
<p><strong>Temporada de turismo</strong>: Julio es un mes en el que muchas ciudades experimentan un aumento en el turismo. Los visitantes que no son residentes pueden optar por utilizar las bicicletas de alquiler para explorar la ciudad y conocer sus lugares de interés.</p>
</li>
<li>
<p><strong>Actividades al aire libre</strong>: En julio, el clima suele ser agradable en muchas regiones, lo que podría impulsar a más personas a participar en actividades al aire libre, como paseos en bicicleta.</p>
</li>
</ul>
<div align='center'>
<img src='https://img.freepik.com/vector-premium/mujer-montando-bicicleta-parque_25030-50403.jpg' width=300 style='border-radius:20px;'>
</div>
<ul>
<li><strong>Eventos y festivales de verano</strong>: Julio puede ser un mes en el que hay una mayor cantidad de eventos y festivales de verano que atraen a residentes y visitantes por igual, lo que puede aumentar la demanda de bicicletas para llegar a estos eventos.</li>
</ul>
<div align='center'>
<img src='https://hostingweb.com.co/2020//images/pagebuilder/slideshow/biker-animated.gif' width=300 style='border-radius:20px;'>
</div>
<hr>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Es importante destacar que las diferencias entre los meses más frecuentes para <strong>miembros anuales</strong> y <strong>ciclistas ocasionales</strong> pueden estar influenciadas por factores como el clima, eventos locales, vacaciones y actividades estacionales.</p>
<p>Estás tendencias son cruciales para <strong>Cyclistic</strong>, ya que les permiten comprender mejor las necesidades y comportamientos de sus usuarios a lo largo del año.</p>
<hr>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Otro dato curioso también es que el día mundial de la bicicleta es el <strong>3 de Junio</strong> Por lo tanto se pueden ir anticipando campañas desde <strong>Abril</strong>, para coincidir con los meses con mayor ventaja polémica.</p>
<div align='center'>
<img src='https://img.freepik.com/vector-premium/dia-mundial-bicicleta-bicicleta-azul-ilustracion-vector-plano-parque_509835-13.jpg?w=2000' width=300 style='border-radius:10px;'>
</div>
<p>También apoyado de esto, presentaremos un análisis del modelo de clustering que habíamos creado, en base a un conjunto muestra obtenido del conjunto total, un modelo que agrupa a los usuarios según sus patrones de uso a lo largo del año.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/16_clustering_of_months_and_users.jpg?raw=true' width=600 style='border-radius:10px;'>
</div>
<p>Podemos observar que el mes con más <strong>ciclistas ocacionales</strong> registrado es <strong>Julio</strong> y con mayor número de registros para los <strong>miembros anuales</strong> es <strong>Marzo</strong>, esto también apunta anteriormente a las conclusiones ya dichas, sobre todo la temporada de calor. Pero son esos meses cruciales para comenzar a prepar las campañas de marketing.</p>
<hr>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>En base a esta información, <strong>Cyclistic</strong> podría aprovechar los meses más activos para implementar estrategias de promoción, ofertas especiales o eventos temáticos que atraigan a más usuarios y fomenten el uso de bicicletas como una opción de movilidad sostenible y práctica durante todo el año.</p>
<div align='center'>
<img src='https://subicicleta.com/blog/wp-content/uploads/2021/05/subicicleta-eventos-ciclismo.png' width=400 style='border-radius:10px;'>
</div>
<p>Así mismo, podrían considerar ajustar su oferta de servicios y flota de bicicletas según las demandas estacionales para brindar una experiencia óptima a sus usuarios en diferentes momentos del año.</p>
<div align='center'>
<img src='https://pedalia.cc/wp-content/uploads/2018/07/0934EUROBIKE2017.jpg' width=400 style='border-radius:10px;'>
</div>    
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Cómo sabemos, hacer también todas estás implementaciones en un corto plazo implica una inversión de mucho capital, aunque son puntos que se deberían de ir implementando por el crecimiento de muchas empresas nuevas al rededor del mundo con diferentes ofertas cada día en el mercado.</p>
<div align='center'>
<img src='https://www.mobilize.org.br/midias/noticias/bike-do-futuro-e-capaz-de-fazer-fotossintese.jpg' width=400 style='border-radius:10px;'>
</div>
<p>Por ello necesitamos primero saber porqué los <strong>ciclistas ocasionales</strong> comprarían una membresía anual, y al ir obteniendo un mayor número de <strong>miembros anuales</strong>, <strong>Cyclistic</strong> puede ir implementando nuevas bicicletas según las necesidades del mercado.</p>
<hr>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Hasta ahora hemos analizado, cuál es la importancia del uso de las bicicletas compartidas, y cuál es la diferencia que presentan los usuarios de <strong>Cyclistic</strong> en el uso de las bicicletas, así mismo cuáles han sido los meses más afluentes, así como el día y hora de los usuarios.</p>
<p>Entonces, para que nuestra empresa <strong>Cyclistic</strong> pueda lograr sus objetivos, pasemos a contestar la siguiente pregunta.</p>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;text-align:center;font-size:18px;">
<h3 id="2-%C2%BFpor-qu%C3%A9-los-ciclistas-ocasionales-comprar%C3%ADan-membres%C3%ADas-anuales-de-cyclistic"><strong>2. ¿Por qué los ciclistas ocasionales comprarían membresías anuales de Cyclistic?</strong></h3>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Para responder esta pregunta comencemos por observar esta gráfica, en dónde analizaremos la importancia de diferentes características que influyen en la decisión de un usuario para convertirse en socio anual o ciclista ocasional.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/12_features_importances_por_usuario.jpg?raw=true' width=600 style='border-radius:10px;'>
</div>
<hr>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Nuestros datos muestran que la característica más influyente en su decisión de convertirse en socios anuales es la &quot;duración del viaje&quot; (duration_min), con una alta puntuación de importancia de aproximadamente 0.77.</p>
<p>Esto sugiere que aquellos que hacen viajes más largos y frecuentes pueden obtener más beneficios de una membresía anual, ya que tendrían acceso ilimitado a las bicicletas durante todo el año, perfecto para sus desplazamientos diarios o actividades recurrentes.</p>
<p>También observamos que la hora del día es relevante para algunos usuarios. Aquellos que utilizan las bicicletas en horas pico o para desplazamientos diarios pueden encontrar conveniente tener una membresía anual, ya que les brinda una solución práctica y rápida para sus desplazamientos cotidianos en esos momentos clave.</p>
<p>Podemos ver que la duración del viaje es un factor clave, apoyado a esto, recordemos que creamos un modelo también de árboles de decisión y con él, exploramos también la importancia de la duración del viaje y el tipo de bicicleta a la hora de clasificar un usuario.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/11_arbol_de_decision.jpg?raw=true' width=600 style='border-radius:10px;'>
</div>
<p>Esto es ideal para quienes utilizan las bicicletas frecuentemente para ir al trabajo, hacer recados o simplemente disfrutar de paseos largos y relajantes.</p>
<hr>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Así que en la siguiente gráfica examinaremos la importancia de diferentes características que influyen en la elección de tipo de bicicleta para cada usuario.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/13_features_importances_tipo_bicicleta.jpg?raw=true' width=600 style='border-radius:10px;'>
</div>
<hr>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>En cuanto a la elección del tipo de bicicleta, nuevamente la <strong>&quot;duración del viaje&quot;</strong> es un factor importante con una puntuación de importancia de aproximadamente <strong>0.77</strong>.</p>
<p>Esto sugiere que aquellos usuarios que hacen viajes más largos y necesitan una asistencia adicional podrían preferir las bicicletas eléctricas, ya que les permiten cubrir distancias más extensas o superar pendientes con mayor facilidad, brindando una experiencia de viaje más cómoda y eficiente.</p>
<p>En resumen, nuestros datos indican que la <strong>duración del viaje</strong> es un factor clave en la decisión de los <strong>ciclistas ocasionales</strong> para adquirir membresías anuales de <strong>Cyclistic</strong>. Además, la <strong>duración del viaje</strong> también es relevante en la elección del <strong>tipo de bicicleta</strong>, con una preferencia por las <strong>bicicletas eléctricas</strong> para viajes más largos y cómodos.</p>
<p>Estos resultados proporcionan información valiosa a <strong>Cyclistic</strong> para adaptar sus servicios y ofertas, asegurando una experiencia satisfactoria y conveniente para sus usuarios en términos de membresías y elección de bicicletas.</p>
<div align='center'>
<img src='https://cyclingindustry.news/wp-content/uploads/2022/07/light.jpg' width=400 style='border-radius:10px;'>
</div>
<p>Ahora que sabemos como opera nuestro mercado, y conocemos cuál es el comportamiento de nuestros usuarios, e indagamos un poco acerca del porque comprarían una membresía, quiero que pasemos a contestar la última pregunta, y con ella profundizar un poco más al respecto y hacer un resumen acerca de la operación de la campaña de marketing.</p>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;text-align:center;font-size:18px;">
<h3 id="3-%C2%BFc%C3%B3mo-puede-usar-cyclistic-los-medios-digitales-para-influenciar-a-los-ciclistas-ocasionales-a-convertirse-en-miembros"><strong>3. ¿Cómo puede usar Cyclistic los medios digitales para influenciar a los ciclistas ocasionales a convertirse en miembros?</strong></h3>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Primero, quiero hacer unas observaciones, y también quiero mencionar el porque <strong>Ecobici</strong> ha tenido un crecimiento que ha presentado hasta un 73% desde sus comienzos, y son por los siguientes factores.</p>
<div align='center'>
<img src='https://ecobici.cdmx.gob.mx/wp-content/uploads/2022/11/Home-cover-1440x713px.jpg' width=400 style='border-radius:10px;'>
</div>
<p>Tras esta investigación, dimos con que <strong>Ecobici</strong>, ha estado resolviendo las demandas de sus usuarios primero que nada con estrategías de alianza con diferentes sectores, que les ha permitido obtener una mayor capitalización, y con esto el número de bicicletas se expandirá de <strong>6,500 a 9,300</strong> y las <strong>estaciones subirán de 480 a 687</strong>, en un plazo de 6 años.</p>
<p>Estás bicicletas actualmente han sido implementadas con tecnología a la vanguardia del mercado, lo que las hace atractivas y comodas para el desplazamiento de los usuarios.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.publimetro.com.mx%2Fresizer%2FHhQyrrNzE5WzMG2L9VTP0kAtugU%3D%2F1440x0%2Ffilters%3Aformat(jpg)%3Aquality(70)%2Fcloudfront-us-east-1.images.arcpublishing.com%2Fmetroworldnews%2FWRCLKFLBEBC53CPFOC4NG7K6RI.jpg&f=1&nofb=1&ipt=256c52a5c10bfcf9de91aaf9b86a6298ccda3659802b6ce9941a4b2db8abb6d7&ipo=images' width=400 style='border-radius:10px;'>
</div>
<p>Además, al tener una aplicación los beneficios son tanto a nivel logístico como operacional, tanto para usuarios, como para la misma empresa, ya que está, al ser vinculada y operada con una cuenta, la base de datos será más robusta.</p>
<p>En un vistazo rápido de los datos abiertos que otorga <strong>Ecobici</strong>, se puede observar que ellos saben el género, la edad, y otros campos que aportan valor a la hora de hacer un análisis acerca del uso y comportamiento de los usuarios con las bicicletas.</p>
<p>Por lo tanto, sería un excelente inicio abordar estás implementaciones en la empresa <strong>Cyclistic</strong> en un futuro cercano, ya que esto les otorga un mayor control en las bicicletas, y una compresión mayor hacia su mercado y sus usuarios.</p>
</div>
<p>Fuentes: <a href="https://semovi.cdmx.gob.mx/storage/app/media/PPT_Ecobici.pdf">Características de las nuevas bicicletas</a>, <a href="https://politica.expansion.mx/cdmx/2021/12/27/grupo-expansion-a-traves-de-5m2-ampliara-y-modernizara-ecobici">Grupo Expansión</a>, <a href="https://ecobici.cdmx.gob.mx/datos-abiertos/">Datos abiertos Ecobici</a>, <a href="http://www.planverde.cdmx.gob.mx/ecotips/37-movilidad/458-algunas-razones-por-las-que-ecobici-es-un-caso-de-exito.html">Plan verde cdmx</a>.</p>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Si bien, estás implementaciones son a un mediano y largo plazo el futuro de <strong>Cyclistic</strong>, ya que con esto dependerá el seguir en la vanguardia de la demanda del mercado. Pero, dichas implementaciones, requieren de tiempo, de capital y sobre todo de distintas alianzas comerciales entre empresas, así que por el momento, podemos abordar como <strong>Cyclistic</strong> podría ir implementando pequeñas acciones, pero significativas, para que los <strong>ciclistas ocasionales</strong> puedan adquirir una <strong>membresía</strong>.</p>
<p>Hablando un poco acerca de mí, cuento con algo de experiencia dentro del sector publicitario, he trabajado para crear marketing tradicional y marketing digital.</p>
<p>Por ello, quiero mencionar que contamos con muchos puntos a nuestro favor para el crecimiento de nuestra empresa. Como ya lo había mencionado, <strong>Cyclistic</strong> debe de implementar el uso de ambos medios para poder realizar campañas cada vez más efectivas.</p>
<p>Cada persona que esta detras de una pantalla, sigue siendo una persona. Y al final el uso de las bicicletas es una actividad para personas, se que suena algo loco, o redundante, pero para invitar a las personas a sumar un cambio positivo en sus vidas, esto debe de ser una tarea que pase de ser una actividad &quot;individual&quot; a ser una actividad comunitaria.</p>
<p>Y para hablar acerca de ello quiero que veamos las siguientes gráficas:</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/06_top10_estaciones_mas_usadas.png?raw=true' width=600 style='border-radius:10px;'>
</div>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/07_top10_estaciones_finales.png?raw=true' width=600 style='border-radius:10px;'>
</div>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>En esta primer gráfica podemos ver las estaciones con un mayor número de usuarios, que las hemos denominado como las estaciones preferidas, ya que tienen mayor afluencia. En la siguiente gráfica vemos las estaciones más frecuentes en donde terminan los recorridos.</p>
<p>Como vemos, ambas nos otorgan la misma lista de estaciones:</p>
<ul>
<li>Streeter Dr &amp; Grand Ave.</li>
<li>DuSable Lake Shore Dr &amp; North Blvd.</li>
<li>Michigan Ave. &amp; Oak St.</li>
<li>DuSable Lake Shore Dr &amp; Monroe St.</li>
<li>Wells St. &amp; Concord Ln.</li>
<li>Millennium Park.</li>
<li>Clark St. &amp; Elm St.</li>
<li>Theather on the lake.</li>
<li>Kingsbury St. &amp; Kinzie St.</li>
</ul>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>También generamos una gráfica para cada tipo de usuario, para saber cuales son las estaciones más recurrentes en dónde comienzan y terminan sus recorridos. En un futuro proyecto podríamos diseñar gráficas con los valores de geolocalización a tráves de <strong>Python y Google Maps</strong>. Aunque por esté momento vamos a simplificarlo con gráficas estadísticas.</p>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/08_estaciones_mas_usadas.png?raw=true' width=600 style='border-radius:10px;'>
</div>
<div align='center'>
<img src='https://github.com/Cervantes21/Data-Science-Portafolio-Python-/blob/main/images/09_estaciones_finales_por_usario.png?raw=true' width=600 style='border-radius:10px;'>
</div>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>En ellas vemos que para los <strong>miembros anuales</strong> las estaciones más recurrentes con un mayor número de usuarios en donde <strong>comienzan</strong> su recorrido son:</p>
<ul>
<li>Kingsbury St. &amp; Kinzie St.</li>
<li>Clark St. &amp; Elm St.</li>
<li>Wells St. &amp; Concord Ln.</li>
<li>University Ave. &amp; 57th St.</li>
<li>Clinton St. &amp; Washington Blvd.</li>
<li>Ellis Ave. &amp; 60th st.</li>
<li>Loomis St. &amp; Lexington St.</li>
<li>Wells St. &amp; Elm St.</li>
<li>Clinton St. &amp; Madison St.</li>
</ul>
<p>Mientras que en las estaciones más recurrentes en donde <strong>finalizan</strong> los viajes los <strong>miembros anuales</strong> son:</p>
<ul>
<li>Kingsbury St. &amp; Kinzie St.</li>
<li>Clark St. &amp; Elm St.</li>
<li>Wells St. &amp; Concord Ln.</li>
<li>University Ave. &amp; 57th St.</li>
<li>Clinton St. &amp; Washington Blvd.</li>
<li>Clinton St. &amp; Madison St.</li>
<li>Ellis Ave. &amp; 60th st.</li>
<li>Loomis St. &amp; Lexington St.</li>
<li>Wells St. &amp; Elm St.</li>
</ul>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Vemos entonces que para los <strong>ciclistas ocasionales</strong> en donde <strong>comienzan</strong> sus recorridos, las estaciones más recurrentes son:</p>
<ul>
<li>Streeter Dr &amp; Grand Ave.</li>
<li>DuSable Lake Shore Dr &amp; Monroe St.</li>
<li>Millennium Park.</li>
<li>Michigan Ave. &amp; Oak St.</li>
<li>DuSable Lake Shore Dr &amp; North Blvd.</li>
<li>Sheed Aquarium</li>
<li>Theather on the lake.</li>
<li>Wells St. &amp; Concord Ln.</li>
<li>Dusable Harbor.</li>
</ul>
<p>Mientras que en donde <strong>finalizan</strong> sus recorridos los <strong>ciclistas ocasionales</strong> son:</p>
<ul>
<li>Streeter Dr &amp; Grand Ave.</li>
<li>DuSable Lake Shore Dr &amp; Monroe St.</li>
<li>Millennium Park.</li>
<li>Michigan Ave. &amp; Oak St.</li>
<li>DuSable Lake Shore Dr &amp; North Blvd.</li>
<li>Theather on the lake.</li>
<li>Sheed Aquarium</li>
<li>Wells St. &amp; Concord Ln.</li>
<li>Clark St. &amp; Armitage Ave.</li>
</ul>
</div>
<div style="background-color:#d1495b;color:#edae49;font-family:monospace;font-size:16px;">
<p>Ahora con toda la información que hemos obtenido de inicio a fin del proyecto nos permite tener una estrategía adaptada a las necesidades reales de la empresa.</p>
<p>Al hacer la comparativa de mercado con otra empresa, nos ha permitido tener un enfoque mayor a la hora de gestionar e implementar nuestras campañas, por ello concluyamos con lo siguiente.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fvirtual.itpachuca.edu.mx%2Fmoodle%2Fpluginfile.php%2F62991%2Fcourse%2Foverviewfiles%2Fdigital-marketing-omaha.gif&f=1&nofb=1&ipt=bf697c33e4b3f61b94e11ab0a4bc6a7e3e8935ab38b5294390952a50f4a199a1&ipo=images' width=400 style='border-radius:10px;'>
</div>
</div>
<div style="background-color:#edae49;color:#d1495b;font-family:monospace;font-size:16px;">
<p>Primero que nada y ante todo, una de mis recomendaciones para <strong>Cyclistic</strong> sea que comiencen a invertir en una aplicación y comiecen a una transición en donde los mismos datos les aporten información con mayor relevancia para comprender no sólo el uso de las bicicletas, sino quiénes son sus usuarios. Sí son mujeres, hombres, que edad tienen, etc...
Con dicha información sumada a la actual, podrían crear campañas digitales mucho más precizas ya que apuntarían al mercado correcto cada vez más, o bien, aumentar el enfoque del mercado que se esta perdiendo.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmuniorotina.go.cr%2Fimages%2F2020%2F03%2F14%2Fsentisis-connector.gif&f=1&nofb=1&ipt=64ab28f35c998185ae541afa2cb126129e702cc1a2787e341f320c84d8dbf854&ipo=images' width=400 style='border-radius:10px;'>
</div>
<p>Por ello, quiero que primero se tome en cuenta realizar actividades de estrategias de promoción, ofertas especiales o eventos temáticos que atraigan a más usuarios y fomenten el uso de bicicletas como una opción de movilidad sostenible.</p>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fdiariocorreo.pe%2Fresizer%2FuU18Hz4i96fgGDjkgrGkgh5X-QM%3D%2F980x528%2Fsmart%2Ffilters%3Aformat(jpeg)%3Aquality(75)%2Farc-anglerfish-arc2-prod-elcomercio.s3.amazonaws.com%2Fpublic%2FXYWHAVOKBFGU5JUDYDBZTWLAAQ.jpg&f=1&nofb=1&ipt=bf5aaa34ba3d3f8696ac5f485eb9009f9948f92cc4ca98bde1605d197e93d840&ipo=images' width=400 style='border-radius:10px;'>
</div>
<p>Dichos eventos pueden ser preparados desde <strong>Abril</strong>, para poder atender los meses más recurrentes como son: <strong>Julio y Agosto</strong>, así como preparativos de para <strong>Marzo</strong> desde <strong>Enero</strong>. En el cuál el equipo de marketing puede optar por un calendario e ir organizando distintos tipos de eventos.</p>
<p>Dichos eventos promocionales por mencionar algunos ejemplos podrían ser:</p>
<ul>
<li>Regalar agua, o aliarse con una empresa de bebidas, para regalar en las estaciones más recurrentes en donde finalizan los usuarios.</li>
</ul>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.ytimg.com%2Fvi%2Fys69vmwbWrQ%2Fmaxresdefault.jpg&f=1&nofb=1&ipt=79139c1fc54c9d67de97393f05275d6ac81249898ce6b1677a75f4223f3d0222&ipo=images' width=400 style='border-radius:10px;'>
</div>
<ul>
<li>El equipo de marketing, podría hablar con el ayuntamiento y organizar un evento colectivo llamando a la comunidad a tener un día de bicicletas. Para ello podrían semanas antes hacer un descuento relevante en las <strong>membresías</strong>.</li>
</ul>
<div align='center'>
<img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.madrid.es%2FUnidadesDescentralizadas%2FUDCMedios%2Fnoticias%2F2012%2F10Octubre%2F07Domingo%2FNotasprensa%2Ffiestabici%2Fficheros%2FGal_FiestaBicicleta_1.jpg&f=1&nofb=1&ipt=22e09af263dc24d9c5864dbbe68dbe505c73873a07c6cb1537c6348332708117&ipo=images' width=400 style='border-radius:10px;'>
</div>
<ul>
<li>Hacer eventos dinamicos para que las personas tengan la posibilidad de ganar <strong>membresías anuales</strong> y así conozcan más personas los beneficios.</li>
</ul>
<div align='center'>
<img src='https://www.lavozdelsur.es/uploads/s1/12/68/25/1/premio-loteria-navidad-ca-diz-germa-n-mesa00007.jpeg' width=400 style='border-radius:10px;'>
</div>
<p>Dichos eventos pueden ser realizados los días <strong>Miércoles, Viernes y/o Sábado</strong>.</p>
<p>Las personas necesitan ser llamadas de una manera divertida, a esto me refiero que debemos de pasar de verlo como una actividad individual, a una actividad comunitaria.</p>
<hr>
</div>
<div style="background-color:#00798c;color:#edae49;font-family:monospace;font-size:16px;">
<p>Por otro lado, si queremos usar los medios digitales para influenciar correctamente a los usuarios, sí se debería de ir haciendo avances para que se conozca mejor quienes son los usuarios. Por otro lado, se pueden utilizar los medios digitales para incentivar a la comunidad a realizar estas actividades, por medio del uso de plataformas y con medios audiovisuales, se podría crear una campaña en dónde el uso sea enfocado a los beneficios que aporta tener una membresía, una campaña digital, conociendo a los usuarios, en donde esa misma campaña los usuarios cuenten su experiencia, el como se transportan, cuales han sido los beneficios que aportan en su vida. Conociendo a los ya <strong>actuales miembros</strong>, se pueden obtener campañas más organicas y reales, y ellos mismos serán la cara de la empresa que llame a esos <strong>ciclistas ocaciones</strong> a convertirse en <strong>miembros anuales</strong>.</p>
</div>
<div style="background-color:#edae49;color:#00798c;font-family:monospace;font-size:16px;">
<p>Con esto finalizamos este proyecto. Pero con él se han abierto nuevas preguntas, y nuevos caminos que me alegraría en futuro volver a retomar.</p>
</div>
<p>Agradezco infinitamente a <a href="https://inroads.org.mx/">Inroads México</a> por la beca otorgada para convertirme en un <strong>Google Data Analyst Professional</strong> y al <a href="https://platzi.com/">Team Platzi</a> Por todos los excelentes cursos en las carreras de <strong>Data Engineer</strong> y <strong>Data Scientist</strong>.
&quot;&quot;&quot;</p>