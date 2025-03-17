# Proyecto-Analisis-de-Sistemas

## Etapas y Pasos para el Desarrollo
🧠 Fase 1: Planificación
Definir los requisitos y casos de uso.
Seleccionar las tecnologías y herramientas.
Diseñar la arquitectura del sistema.
💻 Fase 2: Desarrollo Backend
Crear endpoints para generar y verificar contraseñas.
Implementar almacenamiento seguro en MariaDB (hashing con bcrypt o Argon2).
Generar códigos QR usando zxing o similar.
Proteger endpoints con JWT y Spring Security.
🖥️ Fase 3: Desarrollo Frontend
Crear una interfaz en React para generar y escanear códigos QR.
Integrar autenticación JWT en el frontend.
Añadir feedback visual para facilitar el uso.
🔒 Fase 4: Seguridad y Pruebas
Probar ataques de fuerza bruta y phishing.
Validar que el cifrado es seguro y efectivo.
Asegurar que los datos no se exponen en las respuestas del backend.
🚀 Fase 5: Despliegue y Mantenimiento
Configurar Docker para facilitar el despliegue.
Realizar monitoreo continuo para detectar vulnerabilidades.
Publicar la aplicación y recopilar retroalimentación de los usuarios.
