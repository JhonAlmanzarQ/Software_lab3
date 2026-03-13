# 📚 Demo Académico — Lab 03

Proyecto desarrollado para el **Lab 03 de Ingeniería de Software III**, enfocado en la implementación del flujo académico mínimo del sistema: **Programa → Asignatura → Grupo → Matrícula**. Además, en una segunda parte, el proyecto fue refactorizado por módulos usando **Ports**, evitando que el módulo de matrículas dependa directamente de repositorios de otros módulos. :contentReference[oaicite:1]{index=1}

## 🚀 Funcionalidades principales

- Gestión de programas
- Gestión de asignaturas
- Gestión de grupos
- Registro de matrículas
- Validación de estudiante y grupo existentes
- Validación de cupo máximo por grupo
- Validación de matrícula no duplicada
- Refactor por módulos usando Ports :contentReference[oaicite:2]{index=2}

## ▶️ Cómo ejecutar

1. Clona el repositorio.
2. Abre el proyecto en tu IDE.
3. Verifica que tengas **Java 21** instalado.
4. Ejecuta la aplicación con Maven o directamente desde Spring Boot.
5. Accede a Swagger para probar los endpoints y a H2 para revisar la base de datos. :contentReference[oaicite:3]{index=3}

## 🔗 URLs útiles

- `http://localhost:8080/swagger-ui.html` → Swagger
- `http://localhost:8080/h2-console` → H2 Console :contentReference[oaicite:4]{index=4}

## 🔌 Ports creados

En la parte de refactor por módulos se crearon los siguientes ports públicos:

- `EstudianteQueryPort`
- `GrupoQueryPort`

Estos ports permiten que el módulo de **matrículas** consulte estudiante y grupo sin inyectar directamente los repositorios de otros módulos. :contentReference[oaicite:5]{index=5}

## ✨ Autor

Proyecto realizado como práctica académica para la materia **Ingeniería de Software III**.
