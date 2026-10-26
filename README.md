MedAlert IoT 💊

Pastillero inteligente con recordatorios móviles y registro en la nube

Descripción del proyecto

MedAlert IoT es un proyecto tecnológico que busca ayudar a las personas a recordar los horarios de sus medicamentos mediante un pastillero inteligente basado en el microcontrolador ESP32.

El sistema propone utilizar alertas sonoras y visuales, un servomotor para controlar el compartimiento de los medicamentos, notificaciones móviles y una plataforma en la nube para registrar la información de las tomas.

Objetivo general

Diseñar e implementar un prototipo de pastillero inteligente basado en tecnología IoT que permita emitir recordatorios, enviar notificaciones y registrar la toma de medicamentos para apoyar el cumplimiento de los tratamientos médicos.

Componentes del proyecto

- ESP32: controla el funcionamiento del sistema.
- Sensor de apertura: permite detectar la apertura del compartimiento.
- Servomotor: controla el mecanismo de apertura.
- Buzzer: genera alertas sonoras.
- LEDs: proporcionan alertas visuales.
- Cables y protoboard: permiten realizar las conexiones.
- Firebase: plataforma propuesta para almacenar los registros.
- MIT App Inventor: herramienta propuesta para desarrollar la aplicación móvil.

Diagrama de arquitectura

       Horarios programados
                |
                v
             ESP32
                |
       +--------+--------+
       | | |
       v v v
  Servomotor LEDs Buzzer
       |
       v
  Compartimiento
                |
                v
            Wi-Fi
                |
                v
            Firebase
                |
                v
       Aplicación móvil
                |
                v
       Usuario o cuidador

Funcionamiento

1. Se programan los horarios de los medicamentos.
2. El ESP32 controla los recordatorios.
3. Se activan las alertas sonoras y visuales.
4. El servomotor controla el mecanismo del compartimiento.
5. El sistema registra las tomas en la nube cuando esta función está implementada.
6. La aplicación móvil permite consultar los registros y recibir notificaciones cuando se haya configurado.

Estructura del repositorio

- "firmware/": código fuente del ESP32.
- "hardware/": diagramas y conexiones electrónicas.
- "docs/": documentación técnica.
- "images/": fotografías del prototipo y capturas de la aplicación.
- "README.md": presentación principal del proyecto.

Integrantes

- María Jimena Vargas López.
- María Alejandra Ocampo Gómez.
- Danna Sofía Romero Vargas.

Asesor: Diego Bautista Pulido.

Institución: Colegio IED Jorge Gaitán Cortés.

Área: Tecnología e Informática.

Curso: 902.

Año: 2026.

Pruebas

Se comprobará el funcionamiento de las alertas, el servomotor, el sensor de apertura, la conexión Wi-Fi y el registro de información. Los resultados se agregarán después de realizar las pruebas del prototipo.

Evidencias

En la carpeta "images/" se agregarán fotografías reales del pastillero, sus conexiones y la aplicación móvil.

Referencias

- Firebase: https://firebase.google.com/docs
- Arduino: https://docs.arduino.cc/
- Espressif Systems: https://docs.espressif.com/
- MIT App Inventor: https://appinventor.mit.edu/

MARIA ALEJANDRA OCAMPO GOMEZ <est.mariaocampo@iedjgc.edu.co>
15:40 (hace 1 minuto)
para mí

Materiales del prototipo

- Microcontrolador ESP32.
- Protoboard.
- Sensor ultrasónico HC-SR04.
- Pantalla LCD.
- Servomotor.
- Cables de conexión.
- Resistencias y componentes electrónicos auxiliares.

Funcionamiento del sistema

MedAlert IoT es un pastillero inteligente diseñado para ayudar a recordar los horarios de los medicamentos. El ESP32 controla los componentes electrónicos y permite desarrollar funciones de recordatorio y registro. El sensor ultrasónico puede utilizarse para detectar objetos o la presencia de una mano, según la programación. La pantalla LCD permite mostrar información y el servomotor puede accionar un compartimiento.

Las notificaciones móviles y el almacenamiento en la nube dependerán de la programación y de la conexión a internet implementadas.

Estructura del repositorio

- "firmware/": código fuente del ESP32.
- "hardware/": esquemas y diseños electrónicos.
- "docs/": documentación técnica del proyecto.
- "images/": fotografías del prototipo y capturas de pantalla.
- "README.md": descripción y guía del proyecto.

Integrantes del equipo

1. alejandra ocampo 1
2. jimena vargas 2
3. sofia romero 3 

Estado del proyecto

El proyecto se encuentra en etapa de desarrollo del prototipo electrónico. Se deben verificar las conexiones, programar el microcontrolador y comprobar el funcionamiento de los recordatorios y demás funciones propuestas.
