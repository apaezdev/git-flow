# Git Flow

Andres Paez
Fernando Vaca haciendo el push en la rama 

Un proyecto Node.js moderno para gestión de flujos de trabajo Git.

## 📋 Descripción

Este proyecto implementa un sistema de gestión de flujos de trabajo Git, proporcionando herramientas y utilidades para optimizar el proceso de desarrollo colaborativo.

## 🚀 Características

- ✅ Gestión automatizada de ramas
- ✅ Integración con flujos de trabajo Git Flow
- ✅ Validación de commits
- ✅ Herramientas de merge automatizado
- ✅ Reportes de estado del repositorio

## 📦 Instalación

### Prerrequisitos

- Node.js (versión 18 o superior)
- npm (versión 8 o superior)
- Git (versión 2.30 o superior)

### Instalación local

```bash
# Clona el repositorio
git clone https://github.com/apaezdev/git-flow.git

# Navega al directorio del proyecto
cd git-flow

# Instala las dependencias
npm install
```

### Instalación global

```bash
npm install -g git-flow
```

## 🔧 Configuración

1. Copia el archivo de configuración de ejemplo:

```bash
cp .env.example .env
```

2. Edita el archivo `.env` con tus configuraciones:

```env
# Configuración del repositorio
REPO_PATH=./
DEFAULT_BRANCH=main
DEVELOPMENT_BRANCH=develop

# Configuración de branches
FEATURE_PREFIX=feature/
HOTFIX_PREFIX=hotfix/
RELEASE_PREFIX=release/
```

## 🎯 Uso

### Comandos básicos

```bash
# Inicializar git flow en el repositorio
npm run init

# Crear una nueva feature
npm run feature:start nombre-feature

# Finalizar una feature
npm run feature:finish nombre-feature

# Crear un hotfix
npm run hotfix:start version

# Crear un release
npm run release:start version
```

### Ejemplos de uso

```bash
# Ejemplo: Crear una nueva característica
npm run feature:start user-authentication

# Ejemplo: Finalizar y mergear una característica
npm run feature:finish user-authentication

# Ejemplo: Crear un hotfix para bug crítico
npm run hotfix:start 1.2.1


asdasd
```

## 🧪 Testing

```bash
# Ejecutar todos los tests
npm test

# Ejecutar tests en modo watch
npm run test:watch

# Ejecutar tests con cobertura
npm run test:coverage

# Linter
npm run lint

# Formatear código
npm run format
```

## 📁 Estructura del proyecto

```
git-flow/
├── src/
│   ├── commands/          # Comandos CLI
│   ├── utils/             # Utilidades
│   ├── config/            # Configuración
│   └── index.js           # Punto de entrada
├── tests/                 # Tests unitarios
├── docs/                  # Documentación
├── .env.example           # Ejemplo de configuración
├── .gitignore            # Archivos ignorados por Git
├── package.json          # Dependencias y scripts
└── README.md             # Este archivo
```

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor sigue estos pasos:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -am 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

### Guías de contribución

- Sigue las convenciones de código existentes
- Escribe tests para nuevas funcionalidades
- Actualiza la documentación según sea necesario
- Usa commits descriptivos siguiendo [Conventional Commits](https://www.conventionalcommits.org/)

## 📋 Scripts disponibles

| Script           | Descripción               |
| ---------------- | ------------------------- |
| `npm start`      | Inicia la aplicación      |
| `npm run dev`    | Inicia en modo desarrollo |
| `npm test`       | Ejecuta los tests         |
| `npm run build`  | Construye la aplicación   |
| `npm run lint`   | Ejecuta el linter         |
| `npm run format` | Formatea el código        |

## 🌟 Roadmap

- [ ] Interfaz web para gestión visual
- [ ] Integración con GitHub/GitLab APIs
- [ ] Soporte para múltiples repositorios
- [ ] Notificaciones por email/slack
- [ ] Métricas y analytics

## 🐛 Problemas conocidos

- Compatibilidad limitada con versiones antiguas de Git
- Rendimiento en repositorios muy grandes

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👥 Autores

- **Sebastian Paez** - _Desarrollo inicial_ - [apaezdev](https://github.com/apaezdev)

## 🙏 Agradecimientos

- Equipo de Git Flow original
- Comunidad de Node.js
- Contribuidores del proyecto

## 📞 Contacto y Soporte

- **Issues**: [GitHub Issues](https://github.com/apaezdev/git-flow/issues)
- **Email**: sebastian.paez@example.com
- **Documentación**: [Wiki del proyecto](https://github.com/apaezdev/git-flow/wiki)

---

⭐ Si este proyecto te ha sido útil, ¡considera darle una estrella en GitHub!
