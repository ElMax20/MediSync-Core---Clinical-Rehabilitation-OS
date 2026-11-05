# MediSync Core - Clinical & Rehabilitation OS
## 📌 Descripción del Proyecto
[Resumen del software, justificación de la arquitectura multiplataforma y dominio
dual]
## 👥 Integrantes y Roles
- **Carlos Max Campoverde B:** Líder Técnico / DevOps (Setup Tauri/Electron, CI/CD, Builds)
- **Jorge Calle:** Arquitecto de Base de Datos y Backend (PostgreSQL, SQLite,
Sync API)
- **Sebastián Menoscal:** Desarrollador Frontend - Módulo Enfermería (UI/UX, Triage,
Kardex)
- **Isaac Alfredo Izurieta B:** Desarrollador Frontend - Módulo Fisioterapia (UI/UX,
Goniometría, Rutinas)
## 🏗 Arquitectura del Sistema
- Stack Tecnológico (Frontend, Contenedor Multiplataforma, Motores de BD)
- Diagrama de Arquitectura Offline-First y Motor de Sincronización
## 🚀 Requisitos e Instalación
### Para Desarrollo
git clone https://github.com/usuario/medisync-core.git
cd medisync-core
npm install
npm run dev
### Para Ejecución (Binarios Compilados)
- **Windows:** Enlace a descargables `.msi` / `.exe` en GitHub Releases.
- **Linux:** Enlace a descargables `.AppImage` / `.deb`.
- **Web:** URL de acceso directo.
## 📊 Cobertura de Módulos
- [x] Autenticación y Control de Roles (Admin, Enfermero, Fisioterapeuta)
- [x] Operativa Offline / Sincronización al reconectar
- [x] Áreas Clínicas:
- Enfermería: Signos Vitales, Kardex, Ocupación de Camas.
- Fisioterapia: Goniometría, Escala Daniels, Rutinas de Rehabilitación.
## 📄 Documentación y Manuales
- [Enlace a Manual de Usuario (PDF)](./docs/manual-usuario.pdf)
- [Enlace a Manual Técnico (PDF)](./docs/manual-tecnico.pdf)
## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT.
