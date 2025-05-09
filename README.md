PasswordPanel - Panel de Generación y Seguridad de Contraseñas
PasswordPanel es un componente de Java Swing diseñado para crear y gestionar contraseñas con opciones de visibilidad, generación automática y evaluación de seguridad. Este panel incluye un campo de entrada para contraseñas, iconos interactivos para mostrar/ocultar el texto, generar una contraseña aleatoria y un indicador visual de la seguridad de la contraseña.

Características principales
Campo de Contraseña: Usa JPasswordField para la entrada de contraseñas, con un tamaño predeterminado de 15 caracteres. Permite alternar entre la visibilidad y el modo oculto de la contraseña.

Alternar Visibilidad de Contraseña: Usa un ícono que permite al usuario alternar entre ver y ocultar la contraseña mediante un click.

Generación de Contraseñas Aleatorias: Incluye un generador de contraseñas que permite especificar la longitud y los tipos de caracteres (mayúsculas, minúsculas, números y caracteres especiales).

Evaluación de Seguridad de la Contraseña: Evalúa el nivel de seguridad de la contraseña y lo muestra visualmente mediante un mensaje de texto que cambia de color según el nivel de seguridad (baja, media o fuerte).
## Componentes del Código
Configuración de Imágenes:

![image](https://github.com/user-attachments/assets/bf439d72-0b94-407e-b5e5-bfd867ebee87)

Carga tres imágenes (mostrar, ocultar y generar) para los iconos de alternar visibilidad y generar contraseña.

Campo de Contraseña (JPasswordField):

![image](https://github.com/user-attachments/assets/f9cdec7d-cbda-42f0-a3eb-5c61bba68002)

Usa JPasswordField para la entrada de la contraseña, con el texto oculto por asteriscos (*) de manera predeterminada.
Añade un DocumentListener que actualiza el nivel de seguridad de la contraseña cada vez que se modifica el texto en el campo.
Para evaluar características como longitud, inclusión de mayúsculas, minúsculas, números y caracteres especiales.
La seguridad se clasifica en "Baja", "Media" o "Fuerte" y se indica visualmente cambiando el color del texto de la etiqueta seguridadLabel.

El código incluye un método main para ejecutar la clase PasswordPanel de forma independiente. Al ejecutar el código, se abrirá un JFrame con el panel de contraseña y sus funcionalidades:

![image](https://github.com/user-attachments/assets/ac82c3fe-05b5-4ce6-9ba3-29555356bb52)


## Visualización del propio componente 
![image](https://github.com/user-attachments/assets/1cc890f4-97ad-49d1-bc8f-d8d602713550)
