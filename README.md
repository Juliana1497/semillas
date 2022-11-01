# semillas
semillas
READ ME 

Este es un proyecto realizado por Juliana Cristancho, Maria Suescum y Andrea Niño para la creación de semillas una Fundación que desea saber el estado de ánimo sus alumnos frente a los diplomados de desarrollo sostenible que ofrecen y querer suministrarles una herramienta de fácil manejo, donde puedan organizar las tareas diarias propuestas por la institución.

Una vez se nos facilitaron los requerimientos del cliente frente a la creación de la página SabujCha nos organizamos definiendo los roles en el equipo utilizando la metodología Scrum, para tales fines, los roles se asignaron así:

Product Owner: Juliana Cristancho
Scrum master: Andrea Niño
Team: Maria Suescum

Definidos los roles empezamos la creación del product backlog para definir las tareas a realizar en el equipo y dividimos el desarrollo del proyecto en 4 sprints; 

En el primer Sprint el cual lo llamamos como la etapa de investigación, debido a que se tenía que desplegar un dashboard frente a las emociones sentidas en un diplomado de desarrollo sostenible indagamos sobre los pensum existentes en dicho tema y decidimos tomar como referencia el curso CIENCIAS AMBIENTALES PARA LA TOMA DE DECISIONES de la Universidad Panamericana de estudios superiores para maquetar en concordancia con los módulos del curso los cuales son: 

Módulo 1: Liderazgo Ambiental  32 horas
Módulo 2: Ciencias Ambientales  32 horas
Módulo 3: Finanzas Ambientales  32 horas
Módulo 4: Mercados y emprendimientos Socio-ambientales 32 horas

Luego de definir el contenido técnico del dashboard con base a los diseños encontrados en pinterest, creamos un skecth para la creación de nuestro dashboard y realizamos una lluvia de ideas para ir maquetando una idea general de lo que queríamos desarrollar, el resultado fue el siguiente, diseño el cual maquetariamos posteriormente en Figma:


![photo1667268438](https://user-images.githubusercontent.com/112361979/199144141-4fe72ee3-7c68-4571-88f5-e19645294ef5.jpeg)
![photo1667268438 (1)](https://user-images.githubusercontent.com/112361979/199144266-fb86f9e7-8f61-4c33-9c18-d5cb3ecb0f5d.jpeg)

Así mismo desde la etapa previa a la maquetación definimos de qué manera realizar la evaluación del estado anímico del estudiante, para tal fin, decidimos manejar unas preguntas de satisfacción del estudiante frente a tres grupos generales a evaluar frente a una clase, estos fueron:

Evaluación frente al contenido de la clase
Evaluación frente al profesor
Evaluación frente al alumno

En cada uno de ellos se dio la oportunidad al estudiante de realizar una votación frente a tres preguntas que se desprendían de cada grupo. Las preguntas que utilizamos para evaluar fueron las siguientes:

Evaluación frente al contenido de la clase
¿Cómo valorarías el nivel general de la clase?
¿Qué te pareció el ritmo de la clase?
¿Lo visto en clase te parece útil para el futuro?

Evaluación frente al profesor
¿Qué tan satisfecho estás sobre el desempeño del profesor?
¿El profesor desarrolló el contenido de la clase?
¿Qué tan satisfecho estás con el trato brindado por el profesor?

Evaluación frente al alumno
¿Cómo evalúas la disposición de tus compañeros de clase?
¿Estás satisfecho con la formación que estás recibiendo?
¿La distribución del tiempo en la clase te pareció equitativo?

La votación realizada por el estudiante y proyectada en el dashboard se evidenciaria con un tacómetro en donde de podría ver la respuesta brindada por el estudiante siendo rojo; carita triste malo, amarillo: carita regular, medianamente conforme, verde: carita feliz, bueno.

![photo1667268438 (2)](https://user-images.githubusercontent.com/112361979/199144414-c9bd6f16-435f-4ac9-828d-5e9ac818ff35.jpeg)

Teniendo como base los elementos mínimos tanto en contenido como en  estructuración empezamos con la etapa del sprint 2 de maquetación mockups en figma en escala celular, tableta y escritorio. El resultado fue el siguiente:

![photo1667268438 (3)](https://user-images.githubusercontent.com/112361979/199144553-1b4fe0fc-be3a-4e13-8fef-26b623db8e9f.jpeg)

En la maquetación decidimos utilizar un header a lado izquierdo de todo el screen, junto con su menú de navegación en el cual se podría buscar en “procesos” el nombre del diplomado hasta los estudiantes que hacen parte de él, también acceder a los ajustes de la cuenta, usuario y cerrar sesión.

En el main incluimos los datos básicos de información del estudiante y las valoraciones realizadas por clase en el diplomado, las cuales se podrían ver de dos maneras: la primera, el promedio de las 3 preguntas realizadas al estudiante y la segunda, desplegar pregunta por pregunta arrojando el resultado dado por el estudiante a cada una de ellas. 

Frente a las tareas a realizar implementamos un diagrama circular para que el estudiante pudiera ver las tareas asignadas y entregadas junto con otra valoración del mismo frente a sus emociones frente a las tareas asignadas.

En el footer pusimos las redes sociales de la Fundación Semillas; Una vez estructurado el wireframe realizamos el mockup aplicando los colores y tipografías solicitadas por el cliente, el resultado fue el siguiente:

![photo1667268438 (4)](https://user-images.githubusercontent.com/112361979/199144638-b46550cb-55bf-497d-b7ad-a1f97fbbda42.jpeg)

Finalizada la etapa de maquetación proseguimos con el sprint 3, es decir con la estructuración del HTML para tal finalidad separamos su desarrollo así:

Tareas por realizar en el HEAD: Linkeado de CSS, linkeado de Fonts, cambio del title.
Tareas frente al BODY: Desarrollo del header, del main y el footer.

En principio creamos el repositorio y se realizó la debida creación de las ramas de los diferentes miembros del team, el trabajo fue repartido de tal manera que fuera equitativo, 
también se crearon los documentos base tales como el index.html, estilos.css y la carpeta de imágenes.

Frente al HTML lo primero que realizamos fue la estructuración dle mismo con las etiquetas semánticas, y en el header ahora bien como tal en el HTML en el header realizamos el linkeado de las fuentes de google y del css, también cambiamos el title.

![1](https://user-images.githubusercontent.com/112361979/199146745-f2746cfb-fef1-464e-b1a7-fae3d920c39f.png)

En el CSS aplicamos los estilos generales así:

![2](https://user-images.githubusercontent.com/112361979/199147336-1ed455aa-961f-4456-8d39-9c50c65e2dc3.png)

Una vez subidos los archivos base al repositorio cada una trabajo en su rama en la parte correspondiente. En cada aparte asignado se realizó lo siguiente:

HEADER: Para el header se utilizó una barra de navegación con una lista desordenada por dentro la cual se dividía en 4 partes: Usuario, procesos, ajustes y cerrar sesión. Dentro del aparte de procesos utilizamos la etiqueta de details, para hacer un menú desplegable de los diplomados ofrecidos por la fundación así como de sus estudiantes. Dicha barra de navegación en la versión mobile se desplegó mediante un hover aplicado al header el cual aumentaba su tamaño y lo hacía mediante una animación.

![8](https://user-images.githubusercontent.com/107644961/199152966-76cee837-7e02-4c52-9806-62e7e1d84ff9.PNG)

Para la primera parte del main implementamos el titulo del diplomado junto con la imagen y datos básicos del estudiante
MAIN - PARTE 1 - VALORACIÓN DE LA CLASE:

Para esta parte se utilizaron varias clases y etiquetas. 
Para modificar el ‘módulo-1’ se utilizaron las siguientes propiedades:

![3](https://user-images.githubusercontent.com/112361979/199147411-51a1b3b9-8994-42ed-ba1c-7f6a86c7f53e.png)

Para modificar el título ‘VALORACIÓN DEL ESTADO DEL ÁNIMO’ utilice la clase ‘estado-ánimo’ y  las siguientes propiedades para ajustarla a la maqueta realizada en figma:

![4](https://user-images.githubusercontent.com/112361979/199147485-79937cc2-4d45-4eed-8a6c-96e3e53a8b64.png)

Para poder realizar el hexágono donde se expone el promedio de las preguntas de cómo se siente el estudiante en relación al contenido de la clase, al profesor y al alumno se utilizaron las siguientes clases y propiedades:

![5](https://user-images.githubusercontent.com/112361979/199147627-7a34b785-6d23-46c8-9fe8-1ebca7422935.png)

Para los ‘emojis’ del estado de ánimo de todo el documento, se utilizaron las siguientes clases, etiquetas y propiedades:

![6](https://user-images.githubusercontent.com/112361979/199147675-ec7e7ae9-f9f6-4251-939a-28425e75a442.png)
![7](https://user-images.githubusercontent.com/112361979/199147729-39adbe6e-1b6b-402b-b0a9-dc4c1f838cda.png)

Para personalizar los emojis dentro del hexagono y poner la animaciones de cambio de color, cambio de expresión en la boca del emoji se utilizo el ‘id’ ‘emoji-animo’ y se utilizo así los keyframes:

![8](https://user-images.githubusercontent.com/112361979/199147790-c8ec70cc-80f4-46d0-952b-62f11e8f625e.png)
![9](https://user-images.githubusercontent.com/112361979/199147804-59828efa-4cc1-4f4e-a09e-c68bb5415cb5.png)
![10](https://user-images.githubusercontent.com/112361979/199147814-9ce8c116-d3c2-4694-a512-34b1fdddd32f.png)

Para modificar las listas desplegables de las preguntas de cómo se siente el estudiante en relación al contenido de la clase, al profesor y al alumno se utilizaron las siguientes clases y propiedades, incluyendo la figura de la gota azul en cada número:
![11](https://user-images.githubusercontent.com/112361979/199147858-530388f0-08eb-4944-9c7b-a46eb6e6befd.png)

Para realizar el tacómetro que está en cada pregunta se utilizó la clase ‘tacómetro’ y las siguientes propiedades así. Además, se utilizó una animación para el movimiento de la aguja del tacómetro con el siguiente keyframe: 
![12](https://user-images.githubusercontent.com/112361979/199147937-cf9be8fa-3314-4bab-9604-998935ff5307.png)
![13](https://user-images.githubusercontent.com/112361979/199147945-b6e03499-f869-4ed5-86c3-333a36bbd827.png)

Adicionalmente se personalizaron los ‘emojis’ dentro del tacómetro así:
![14](https://user-images.githubusercontent.com/112361979/199147988-0b52f1f2-3b86-428a-b91a-69cd7937e468.png)
![15](https://user-images.githubusercontent.com/112361979/199147993-fcc7990e-e67b-4c98-a853-fd58b5555657.png)

MAIN - PARTE 2 - ORGANIZACIÓN DE TAREAS:

Para realizar  esta parte  aplicamos diferentes div para orientar a cuadros cada sección
<img width="429" alt="16" src="https://user-images.githubusercontent.com/112361979/199148089-3c089144-dc41-4909-abfd-07f7a7b20f4e.png">
para  la creación del tabulador de torta  se utilizaron los siguientes estilos


para las animaciones  del tabulador aplicamos los siguientes estilos para 
<img width="403" alt="17" src="https://user-images.githubusercontent.com/112361979/199148176-2ef591e1-793e-4ccc-839a-e40e359f40a7.png">

Para realizar el gradiente se aplicaron  las siguientes propiedades  al igual  que la función de animaciones para  visualizar los diferentes porcentajes en colores de estado de cada estudiante 
<img width="680" alt="18" src="https://user-images.githubusercontent.com/112361979/199148235-42c4060b-ee6a-481e-a755-16e4abc4148f.png">

para la animaciones se utilizó los siguiente keyframe:
<img width="719" alt="19" src="https://user-images.githubusercontent.com/112361979/199148283-e25b10ef-de23-4a0d-afdd-fa051bb61c40.png">

para esta sección también utilizamos  animate face con el estado de animo de cada estudiante aplicando rojo para la face cry, amarillo para la face serius y verde para la face happy, donde se utilizaron diferentes propiedades en css para  formar las caritas

<img width="223" alt="20" src="https://user-images.githubusercontent.com/112361979/199148354-d1ac7500-8491-4fe3-a62c-fd46511364c3.png">

para la creación de los lips de cada emoji se utilizó la siguiente propiedades dependiendo del estado de ánimo.

Cry:
<img width="188" alt="21" src="https://user-images.githubusercontent.com/112361979/199148382-38135a03-139c-4dc3-bf10-e41181de1b66.png">

Serious:
<img width="203" alt="22" src="https://user-images.githubusercontent.com/112361979/199148429-84ada6aa-696a-43e0-919f-c54805dc553c.png">

Happy:
<img width="205" alt="23" src="https://user-images.githubusercontent.com/112361979/199148483-2ee5c396-28b7-4507-8f60-d5ad6faf3462.png">

 luego utilizamos la etiqueta summary para la creación de los demás módulos del:
<img width="188" alt="24" src="https://user-images.githubusercontent.com/112361979/199148513-94bd172f-5b9e-4ab5-a47e-9753d2c7f695.png">

también se aplico un spam en esta etiqueta para crear un arrow y se visualizará  en paralelo con el texto:
<img width="156" alt="25" src="https://user-images.githubusercontent.com/112361979/199148551-a3fe592f-e610-4f8d-a043-ff3796f33b08.png">

FOOTER: 
 Para esta sección utilizamos div  para orientar  por cajas en donde se implemento las redes sociales de la institución y los derechos reservados en donde se utilizaron los siguientes estilos en css:
<img width="173" alt="26" src="https://user-images.githubusercontent.com/112361979/199148598-263a1caa-f0f9-411c-8000-be6db6a855a4.png">

se aplicó position fixed para que el footer quedará fijo y no hiciera scroll al momento de desplazarse por la app al igual que display flex para organizar los elementos en el espacio destinado.

Para finalizar, realizamos los diferentes commits y merge necesarios para ir unificando el proyecto y así obtener una página prototipada en HTML y CSS en GitHub pages la cual se puede visualizar en el siguiente link: https://juliana1497.github.io/semillas/











