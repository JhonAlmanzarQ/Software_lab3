# 📚 Demo Académico — Lab 03

Proyecto desarrollado para el **Lab 03 de Ingeniería de Software III**, enfocado en la implementación del flujo académico mínimo del sistema: **Programa → Asignatura → Grupo → Matrícula**. Además, en una segunda parte, el proyecto fue refactorizado por módulos usando **Ports**, evitando que el módulo de matrículas dependa directamente de repositorios de otros módulos.

## 🚀 Funcionalidades principales

- Gestión de programas
- Gestión de asignaturas
- Gestión de grupos
- Registro de matrículas
- Validación de estudiante y grupo existentes
- Validación de cupo máximo por grupo
- Validación de matrícula no duplicada
- Refactor por módulos usando Ports

## ▶️ Cómo ejecutar

1. Clona el repositorio.
2. Abre el proyecto en tu IDE.
3. Verifica que tengas **Java 21** instalado.
4. Ejecuta la aplicación con Maven o directamente desde Spring Boot.
5. Accede a Swagger para probar los endpoints y a H2 para revisar la base de datos.

## 🔗 URLs útiles

- `http://localhost:8080/swagger-ui.html` → Swagger
- `http://localhost:8080/h2-console` → H2 Console

## 🔌 Ports creados

En la parte de refactor por módulos se crearon los siguientes ports públicos:

- `EstudianteQueryPort`
- `GrupoQueryPort`

Estos ports permiten que el módulo de **matrículas** consulte estudiante y grupo sin depender directamente de los repositorios de otros módulos.

## ✨ Autor

Proyecto realizado como práctica académica para la materia **Ingeniería de Software III**.
