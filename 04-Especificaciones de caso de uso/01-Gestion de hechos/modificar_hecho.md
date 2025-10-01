# Caso de Uso: Modificar Hecho

- **Actor Principal:** Administrador.
- **Descripción:** Permite al usuario modificar un hecho existente.
- **Precondiciones:** El usuario debe estar autenticado y debe haber ingresado a la gestión de hechos.

---

## Camino Principal

1. El usuario selecciona el hecho.
2. El usuario clickea el botón “Modificar hecho”.
3. el sistema muestra el nombre actual del hecho y pide un nuevo nombre.
4. El administrador ingresa los nuevos datos.
5. El sistema  el sistema valida que tenga caracteres, que el nombre no esté repetido y actualiza la información.

---

## Caminos Alternativos

X.2 Cancelación del usuario:**  
  El usuario puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

5.1 Error de validación:**  
  El sistema detecta que no ingreso datos o estan repetidos y lo envía nuevamente al paso 3.

---

- **Postcondición:** Hecho modificado.
