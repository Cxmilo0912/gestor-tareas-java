markdown
# 📝 Gestor de Tareas Simple
Aplicación de consola en Java para gestionar tareas, desarrollada colaborativamente
usando Git y GitHub.
## 👥 Equipo de Desarrollo
- **Miembro 1:** Funcionalidad de agregar tareas
- **Miembro 2:** Funcionalidad de listar tareas
- **Miembro 3:** Funcionalidad de marcar como completadas
- **Miembro 4:** Funcionalidad de eliminar tareas y persistencia en archivo
## ⚙️ Requisitos
- Java JDK 8 o superior
- Git (opcional, para desarrollo)
## 🚀 Cómo Compilar y Ejecutar
```bash
# 1. Clonar repositorio (si aún no lo tienes)
git clone https://github.com//gestor-tareas-java.git
cd gestor-tareas-java
# 2. Compilar
javac -d bin src/app/*.java
# 3. Ejecutar
java -cp bin app.Main
```
## 📦 Funcionalidades
✅ **Agregar tareas** con descripción y fecha límite
✅ **Listar todas las tareas** con su índice y estado
✅ **Marcar tareas como completadas** por índice
✅ **Eliminar tareas** por índice
✅ **Persistencia automática** - las tareas se guardan al salir y se cargan al iniciar
## 📂 Estructura del Proyecto
```
gestor-tareas-java/
├── README.md
├── .gitignore
├── src/
│ └── app/
│ ├── Main.java # Programa principal con menú
│ ├── Tarea.java # Clase que representa una tarea
│ └── GestorTareas.java # Clase que gestiona las operaciones
├── bin/ # Archivos compilados (.class)
└── tareas.txt # Archivo de persistencia (generado automáticamente)
```
## 🎮 Uso de la Aplicación
```
════════════ MENÚ ════════════
1. ➕ Agregar tarea
2. 📄 Listar tareas
3. ✔️ Marcar como completada
4. 🗑️ Eliminar tarea
5. 🚪 Salir
══════════════════════════════
```
### Ejemplo de uso:
1. Selecciona opción **1** para agregar una tarea
2. Ingresa la descripción y fecha (formato: YYYY-MM-DD)
3. Selecciona opción **2** para ver todas tus tareas
4. Usa los índices [0], [1], [2]... para marcar o eliminar tareas
## 🤝 Flujo de Trabajo con Git
Este proyecto fue desarrollado usando:
- **Ramas independientes** para cada funcionalidad
- **Pull Requests** para revisión de código
- **Code reviews** entre miembros del equipo
- **Merge controlado** a la rama principal
## 📖 Aprendizajes
Durante este proyecto practicamos:
- Trabajo colaborativo con Git y GitHub
- Programación orientada a objetos en Java
- Manejo de archivos para persistencia
- Validación de entrada de usuario
- Resolución de conflictos en control de versiones
