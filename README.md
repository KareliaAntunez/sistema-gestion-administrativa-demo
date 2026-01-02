🧾 Sistema de Gestión Administrativa – Versión Demo

Demo de un sistema de gestión administrativa desarrollado con Laravel y Node.js, enfocado en el ingreso de datos y la generación automática de contratos y pagarés en PDF.
Esta versión demo no contiene datos reales ni identidad visual del sistema productivo; está diseñada para demostrar funcionalidades clave y la estructura del proyecto.

🎯 Propósito

Este proyecto es una versión simplificada y pública de un sistema desarrollado para fines administrativos y financieros. El objetivo principal de la demo es mostrar:

- Formularios de ingreso de datos
- Validaciones de usuario
- Generación automática de documentos PDF (contratos y pagarés)
- Arquitectura modular del sistema

🛠️ Tecnologías Usadas
Área	                Tecnologías
Backend	              Laravel (PHP)
Frontend	            HTML, CSS, JavaScript
PDF	                  jsPDF u otra librería de generación de PDF
Base de Datos	        MySQL (demo)
Control de Versiones	Git / GitHub

🚀 ¿Qué Incluye la Demo?

- 📝 Formularios de ingreso de datos para contratos
- 🧾 Generación de documentos PDF (contratos y pagarés)
- 📂 Estructura de carpetas organizada por módulo
- 🧪 Código base listo para ampliar o adaptar

🧱 Estructura del Proyecto

├── app/                 # Lógica principal del sistema
├── bootstrap/           # Configuración del framework Laravel
├── config/              # Configuraciones del proyecto
├── database/            # Migraciones / Seeds (demo)
├── public/              # Archivos públicos
├── resources/           # Vistas y assets front-end
├── routes/              # Definición de rutas
├── storage/             # Archivos generados
├── tests/               # Pruebas (si existen)
├── README.md            # Este archivo
├── composer.json        # Dependencias PHP
└── package.json         # Dependencias JS

📥 Instalación (entorno local)

Asegúrate de tener PHP, Composer, MySQL y Node.js instalados.

1. Clona el repositorio: git clone https://github.com/KareliaAntunez/sistema-gestion-administrativa-demo.git
2. Instala dependencias de Laravel: composer install
3. Instala dependencias de JavaScript: npm install
4. Copia el archivo de configuración: cp .env.example .env
5. Crea una base de datos local y configura .env:
  DB_HOST=127.0.0.1
  DB_DATABASE=demo_db
  DB_USERNAME=root
  DB_PASSWORD=
6. Genera la clave de aplicación: php artisan key:generate
7. Ejecuta migraciones (si aplica): php artisan migrate
8. Inicia el servidor: php artisan serve

🧾 Uso de la Demo

1. Abre tu navegador en http://localhost:8000
2. Usa los formularios para ingresar datos
3. Genera contratos o pagarés en PDF
4. Revisa los PDF en la carpeta /storage o según diseño

Nota: Esta demo no incluye sistemas de usuario real ni autenticación avanzada.

📌 Notas Importantes

- Esta es una versión de demostración pública y NO contiene datos sensibles
- No es el sistema real original
- Está pensada para fines de aprendizaje, portafolio y evaluación técnica

👩‍💻 Sobre la Autora

Karelia Cecilia Antúnez Rivas
Junior Software Developer | QA Automation | Informática Administrativa
📧 antunezkarelia@gmail.com
🔗 https://www.linkedin.com/in/karelia-cecilia-antunez-rivas-66443b183

