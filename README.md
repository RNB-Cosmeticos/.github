 
# <img src="https://www.rnbcosmeticos.com/wp-content/themes/rnb/img/rnb-footer.jpg" width="80" height="80"/> Bienvenido al repositorio GitHub

Esta organización contiene los repositorios oficiales del departamento de Organización y Sistemas.

## 🌳 Estrategia de ramas

- `main`: código en producción.
- `develop`: rama de integración.
- `feature/*`: nuevas funcionalidades.
- `hotfix/*`: correcciones urgentes.

## ✅ Normas de desarrollo

- No realizar commits directos sobre `main`.
- Todas las modificaciones requieren Pull Request.
- Al menos una aprobación antes del merge.
- Utilizar mensajes de commit descriptivos (`feat:`, `fix:`, `docs:`).
- Mantener actualizado el README de cada repositorio.

## 🔒 Seguridad

- No almacenar contraseñas ni secretos en el código.
- Utilizar variables de entorno o GitHub Secrets.
- Revisar dependencias antes de publicarlas.

## 🔄 Flujo de trabajo

1. Crear rama desde `develop`.
2. Realizar cambios.
3. Crear Pull Request.
4. Revisar y aprobar.
5. Fusionar en `develop`.
6. Promocionar a `main` mediante versión validada.

## 📚 Documentación

Cada repositorio debe incluir:

- README.md
- Descripción funcional
- Requisitos de instalación
- Procedimiento de despliegue
- Historial de versiones
