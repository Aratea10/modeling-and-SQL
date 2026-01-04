# 🏹 Portfolio de Modelado SQL y Bases de Datos

<div align="center">

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![DBEAVER](https://img.shields.io/badge/DBEAVER-382923?style=for-the-badge&logo=dbeaver&logoColor=white)](https://dbeaver.io/)

</div>

## 📖 Descripción

### ¿Qué es este proyecto?

Es un repositorio dedicado al **modelado de bases de datos** y **scripting SQL**, desarrollado como parte del bootcamp de Desarrollo Web FullStack de KeepCoding. Incluye ejercicios prácticos de diseño de esquemas entidad-relación y su implementación en PostgreSQL, destacando casos de uso como la gestión de un **Videoclub** y una **Academia**.

### ¿Por qué lo hice?

- **Objetivo académico**: Profundizar en el diseño de bases de datos relacionales y normalización.
- **Desafío técnico**: Implementar scripts DDL y DML complejos, asegurando la integridad referencial.
- **Práctica real**: Traducir requerimientos de negocio a diagramas técnicos y código SQL funcional.

---

## ✨ Características principales

### 🗄️ Diseño de Bases de Datos

- ✅ **Diagramas E-R** - Modelado visual con Draw.io.
- ✅ **Normalización** - Estructuración eficiente de datos.
- ✅ **Integridad Referencial** - Uso correcto de Primary Keys y Foreign Keys.

### 🐘 Implementación PostgreSQL

- ✅ **Creación de Esquemas** - Organización lógica con `CREATE SCHEMA`.
- ✅ **Tablas y Relaciones** - Definición precisa de tipos de datos y restricciones.
- ✅ **Manipulación de Datos** - Scripts de inserción masiva y consultas.

---

## 🛠️ Stack Tecnológico

| Base de Datos | Diseño     | Herramientas |
|---------------|--------    |--------------|
| PostgreSQL    | Draw.io    | VS Code      |
| SQL (ANSI)    | Modelo E-R | DBeaver      |
|               |            | Git          |

---

## 🚀 Cómo Ejecutar el Proyecto

### Prerrequisitos

- Tener instalado **PostgreSQL** (o acceso a un servidor remoto).
- Un cliente SQL como **DBeaver**, **pgAdmin** o la extensión de bases de datos de VS Code.

### Ejecución de Scripts

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/Aratea10/modeling-and-SQL.git
   ```

2. **Abrir el script deseado**: Ej. `práctica-videoclub/script_videoclub.sql`.

3. **Ejecutar en el cliente SQL**:
   - Conectar a tu instancia de PostgreSQL.
   - Ejecutar el script completo para crear las tablas e insertar los datos.

---

## 📁 Estructura de Archivos

```text
modeling-and-SQL/
├── 📄 academia.sql
├── 📄 Academia.drawio
├── 📄 Días 2 y 3.pdf
├── 📂 práctica-videoclub/
│   ├── 📄 script_videoclub.sql
│   ├── 📄 videoclub_ER.drawio
│   └── 📄 Enunciado de la práctica.pdf
└── 📂 practical-solution/
    ├── 📄 videoclub.sql
    └── 📄 Diagrama E_R.drawio
```

## 🎓 Aprendizajes y Desafíos

### 💡 Conceptos dominados

- **DDL (Data Definition Language)**: `CREATE`, `DROP`, `ALTER`.
- **DML (Data Manipulation Language)**: `INSERT`, `UPDATE`, `DELETE`, `SELECT`.
- **Restricciones**: `NOT NULL`, `UNIQUE`, `CHECK`, `DEFAULT`.

### 🚧 Desafíos superados

- **Diseño desde cero**: Crear un modelo para un Videoclub considerando copias, socios y préstamos.
- **Manejo de fechas**: Gestión correcta de tipos `DATE` y formatos.
- **Esquemas**: Separación lógica de objetos de base de datos.

## 🤝 Guía de Contribución

¿Tienes ideas para mejorar estos esquemas? ¡Las contribuciones son bienvenidas!

1. Haz fork del proyecto
2. Crea una rama: `git checkout -b feature/mejora-modelo`
3. Commit tus cambios: `git commit -m 'Mejora en tabla socios'`
4. Push: `git push origin feature/mejora-modelo`

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**.

## 👨‍💻 Autor

**Sara Gallego Méndez**
*Estudiante de Desarrollo Web Full Stack y de Administración de Sistemas Informáticos en Red*

## 🌐 Contacto y Redes

- **GitHub**: [Aratea](https://github.com/Aratea10)
- **LinkedIn**: [Sara Gallego Méndez](https://www.linkedin.com/in/sara-gallego-mendez)
- **X**: [@SaraGallegoM10](https://x.com/SaraGallegoM10)

### 🙏 Agradecimientos

- **KeepCoding Bootcamp** - Por la excelente formación en Backend.
