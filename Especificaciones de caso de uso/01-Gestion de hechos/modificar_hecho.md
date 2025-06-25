# Caso de Uso: Modificar Hecho

- **Actor Principal:** Usuario  
- **Descripción:** Permite al usuario modificar un hecho existente.  
- **Precondiciones:** El usuario debe estar autenticado.  

---

## Camino Principal

1. El usuario selecciona el hecho.
2. El usuario clickea el botón “Modificar hecho”.
3. El sistema solicita los nuevos datos.
4. El administrador ingresa los nuevos datos.
5. El sistema valida y actualiza la información.

---

## Caminos Alternativos

X.2 Cancelación del usuario:**  
  El usuario puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

5.1 Error de validación:**  
  El sistema detecta un problema en los datos y lo envía nuevamente al paso correspondiente (por ejemplo, paso 3).

---

- **Postcondición:** Hecho modificado.
