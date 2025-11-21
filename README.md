Sistema de Gestión de Diplomados

Características principales:
• Inicio de sesión por roles: los administradores y alumnos acceden con credenciales distintas.

Módulo de administración:
• CRUD para usuarios, materias y diplomados
• Permite gestionar diplomados, incluyendo la asignación de materias mediante casillas de verificación.
Módulo de alumnos:
• Los alumnos pueden ver los diplomados en los que están inscritos.
• Pueden consultar el catálogo completo de diplomados disponibles.
• Pueden inscribirse a nuevos diplomados, con validación para evitar empalmes de fechas.

Arquitectura del sistema:

Tecnologías utilizadas:
- Lenguaje de programación: Kotlin.
- Base de datos: SQLite.
- Interfaz de usuario: XML de Android con componentes de Material Design.
- Librerías principales: RecyclerView y AlertDialog.
Estructura del código:
- adapters: contiene los adaptadores para RecyclerView.
- data/database: incluye los DAOs y la clase AppDatabaseHelper.
- data/repository: contiene los repositorios.
models: incluye las clases de datos en Kotlin.
Cómo ejecutar la aplicación:
1. Abre el proyecto en Android Studio.
2. Espera a que Gradle sincronice todas las dependencias.
3. Ejecuta la aplicación en un emulador o dispositivo físico.

Nota importante: si se modifican los datos iniciales definidos en AppDatabaseHelper, es necesario reinstalar la aplicación para que la base de datos se cree nuevamente.
Credenciales de prueba:
• Administrador: usuario "admin", contraseña "1234".
• Alumno: usuario "maria", contraseña "pass2".



