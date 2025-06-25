# Caso de Uso: Eliminar Sumariante

- **Actor Principal:** Administrador  
- **Descripción:** Permite al administrador eliminar un sumariante del sistema.  
- **Precondiciones:** El administrador debe estar autenticado.  

---

## Camino Principal

1. El administrador selecciona el sumariante a eliminar.
2. El administrador clickea “Eliminar sumariante”.
3. El sistema pide la confirmación de la eliminación.
4. El usuario clickea en eliminar definitivamente.
5. El sistema confirma la eliminación.

---

## Caminos Alternativos

X.2 Cancelación del administrador:**  
  El administrador puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

4.2 Eliminación cancelada:**  
  El usuario decide no eliminar definitivamente, y el sistema lo envía nuevamente al paso 1.

---

- **Postcondición:** El sistema actualiza la base de datos.
