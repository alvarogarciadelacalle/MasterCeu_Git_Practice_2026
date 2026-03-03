# Ejercicio Práctico: Trabajando con Git en Equipo

**Objetivo:** Practicar el flujo de trabajo colaborativo: ramas, Pull Requests y resolución de conflictos.

**Nota:** Si tienes dudas sobre cómo ejecutar algún comando, consulta la *Guía Maestra: Git + VS Code* o tus apuntes de clase.

---

## 🚀 Instrucciones

### 1. Preparación
*   Obtén la URL del repositorio compartido (proporcionada por el profesor) y clónalo en tu PC.

### 2. Trabajo Individual (Sin Conflictos)
*   **Rama:** Crea una rama nueva desde `main` llamada `feature/bio-[tu_nombre]`.
*   **Tarea:** Crea la carpeta `bios_alumnos` (si no existe) y un archivo `[tu_nombre].md` dentro con una breve descripción sobre ti.
*   **Entrega:** Haz Commit, Push y abre una **Pull Request (PR)** en GitHub.

### 3. Trabajo Concurrente (Con Conflictos)
*   **Sincronización:** Vuelve a `main` y haz `git pull` para tener lo último.
*   **Rama:** Crea una rama nueva `feature/peli-[tu_nombre]`.
*   **Tarea:** Edita `data/peliculas_comunes.txt` añadiendo tu película favorita **en la primera línea**.
*   **Entrega:** Haz Commit, Push y abre una PR.
*   **Resolución:** Cuando GitHub detecte el conflicto (porque otro compañero editó la misma línea), usa el botón **Resolve conflicts** de la propia web de GitHub. Edita el archivo para dejar ambas películas (o la que consideres), marca como resuelto (`Mark as resolved`) y completa el **Commit merge**.

### 4. Revisión
*   Verifica en la pestaña **Commits** de tu PR que aparece el commit de merge.

---

## ✅ Checklist de Entrega
- [ ] Tu archivo de biografía está en `main`.
- [ ] Tu película favorita aparece en la lista común.
- [ ] El historial muestra que has resuelto un conflicto de fusión.
