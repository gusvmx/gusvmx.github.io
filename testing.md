# Testing
Todo software que está listo para producción requiere ser verificado antes de salir a producción. Así como la disciplina de desarrollo de software ha madurado, las formas de probar software también han madurado. En vez de tener una cantidad muy grande e indefinida de testers de software con actividades manuales, los equipos de desarrollo se están comenzando a mover hacia automatizar la mayor cantidad de sus esfuerzos de pruebas. El automatizar las pruebas permite a los equipos saber en qué momento dejó de funcionar su software en cuestión de segundos o minutos en lugar de días o semanas.

Este ciclo de retroalimentación que drásticamente ha sido reducido por las pruebas automatizadas va de la mano con prácticas de desarrollo ágiles, integración continua y una cultura DevOps. El tener un enfoque efectivo de prueba de software permite a los equipos ser más rápidos con una mayor certidumbre.

Esta sección explora cómo un portafolio de pruebas debe ser para poder ser responsivo, confiable y sustentable, sin importar si se está construyendo una arquitectura de microservicios, aplicaciones móviles o ecosistemas del Internet de las cosas. También entraremos en detalle a la construcción de pruebas automatizadas efectivas y leíbles.

## La importancia de la automatización (de pruebas)

El software se ha convertido en una parte esencial del mundo en el que vivimos. Ha superado su primer propósito: hacer a los negocios más eficientes. Actualmente las compañías tratan de encontrar formas de convertirse en compañías digitales de primera clase. Como usuarios, cada uno de nosotros interactúa con una cantidad de software en constante crecimiento todos los días. Las ruedas de la innovación giran cada vez con más velocidad.

Si deseamos mantener el paso, tenemos que adoptar nuevas formas para entregar nuestro software más rápido sin sacrificar su calidad. La práctica de Entregas Continuas (CD) donde automáticamente aseguramos que nuestro software puede ser liberado en cualquier momento a producción, nos puede ayudar a lograrlo. Con entregas continuas, utilizamos un pipeline de construcción que automáticamente prueba nuestro software y lo despliega en nuestros ambientes de prueba y de producción.

Construir, probar y desplegar una cantidad de software que está en constante crecimiento más pronto que tarde se vuelve imposible, a menos que deseemos designar mucho tiempo en trabajo repetitivo y manual en vez de entregar software funcional constantemente. Automatizar todo, desde la construcción, pruebas, despliegue e infraestructura, es la única forma de lograrlo.

Un enfoque de pruebas de software tradicional involucra demasiado trabajo manual para desplegar nuestra aplicación hacia un ambiente de pruebas y hasta entonces ejecutar algún tipo de pruebas de caja negra. Por ejemplo, dar click a través de toda la interface para ver si hay algo que dejó de funcionar. Regularmente estas pruebas serían especificadas por scripts de pruebas para asegurar que los testers hicieran una revisión consistente.

Evidentemente el probar todos los cambios manualmente es una tarea muy cara en tiempo, repetitiva y tediosa. La repetición es aburrida, la aburrición nos lleva a cometer errores y nos lleva a la frustración que puede provocar buscar algún nuevo trabajo al acercarse el fin de semana.

Afortunadamente existe un remedio para las tareas repetitivas: la automatización.

Automatizar las tareas repetitivas puede ser un parte-aguas en nuestra vida como desarrollador de software. Automatiza estas pruebas y no necesitarás seguir inconscientemente un protocolo de clicks para saber si nuestro software aún funciona correctamente. Automatiza tus pruebas y podrás cambiar tu código sin temor. Si en algún momento has intentado hacer una refactorización grande sin un conjunto de pruebas adecuado, te apuesto a que sabes en qué tipo de historia de terror se puede convertir. ¿Cómo podrías saber si accidentalmente hiciste que algo dejara de funcionar mientras realizas el cambio? Bueno, haces tantos clicks como casos de pruebas manuales, así es como te das cuenta. Siendo honestos, ¿Realmente disfrutas hacer esos clicks? ¿Qué tal sería hacer cambios a gran escala y saber dónde se descompuso algo en segundos mientras estás tomando un sorbo de café? Si tú me preguntas te diré que este enfoque suena más disfrutable.

