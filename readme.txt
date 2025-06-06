PSP-SMTP-SERVER
Este proyecto es una aplicación desarrollada en Java, como parte de las actividades del módulo de Programación de Servicios y Procesos (PSP). La aplicación implementa un servidor SMTP modificado para enviar correos electrónicos utilizando una cuenta de Gmail, con las librerías actualizadas.

🧠 Descripción
La aplicación permite enviar correos electrónicos a través de un servidor SMTP configurado con Gmail. Utiliza las librerías mail.jar y activation.jar para manejar la comunicación y el contenido de los correos.

📁 Estructura del Proyecto
css
Copiar
Editar
PSP-SMTP-SERVER/
├── Main.java
├── mail.jar
├── activation.jar
├── readme.txt
└── .gitattributes
Main.java: Clase principal que contiene la lógica para enviar correos electrónicos mediante SMTP.

mail.jar y activation.jar: Librerías necesarias para la funcionalidad de envío de correos.

readme.txt: Archivo con instrucciones o información adicional sobre el proyecto.
gist.github.com

🚀 Instrucciones de Ejecución
Clonar el repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-SMTP-SERVER.git
Configurar el proyecto:

Asegúrate de tener Java instalado en tu sistema.

Incluye las librerías mail.jar y activation.jar en el classpath de tu proyecto.

Ejecutar la aplicación:

Compila y ejecuta la clase Main.java.

La aplicación solicitará las credenciales de tu cuenta de Gmail y los detalles del correo a enviar.
github.com
gist.github.com

Nota: Es posible que necesites habilitar el acceso para aplicaciones menos seguras en tu cuenta de Gmail o generar una contraseña de aplicación si tienes la verificación en dos pasos activada.

🛠️ Tecnologías Utilizadas
Java: Lenguaje de programación principal.

JavaMail API: API utilizada para la comunicación SMTP.
github.com

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub
