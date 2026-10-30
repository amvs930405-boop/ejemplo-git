# Ejemplo de uso de Git

Proyecto de práctica para aprender los comandos básicos de Git: crear un repositorio, guardar cambios y revisar el historial.

## Requisitos

- [Git](https://git-scm.com/) instalado
- Nombre y correo configurados:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@correo.com"
```

## Flujo básico

1. **Inicializar el repositorio** (solo una vez):

   ```bash
   git init
   ```

2. **Ver el estado** de los archivos:

   ```bash
   git status
   ```

3. **Agregar archivos** al área de preparación:

   ```bash
   git add README.md    # un archivo
   git add .            # todos los cambios
   ```

4. **Guardar los cambios** con un commit:

   ```bash
   git commit -m "Describe aquí el cambio"
   ```

5. **Revisar el historial**:

   ```bash
   git log --oneline
   ```

## Otros comandos útiles

| Comando | Para qué sirve |
| --- | --- |
| `git diff` | Ver los cambios que aún no se agregaron |
| `git branch nombre` | Crear una rama nueva |
| `git switch nombre` | Cambiar a otra rama |
| `git merge nombre` | Unir una rama con la actual |
| `git restore archivo` | Descartar cambios no guardados de un archivo |

## Subir a GitHub (opcional)

```bash
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin master
```
