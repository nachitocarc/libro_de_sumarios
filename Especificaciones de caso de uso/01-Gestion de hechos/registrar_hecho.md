# Caso de Uso: Registrar Hecho

- **Actor Principal:** Sumariante  
- **Descripción:** Permite al sumariante registrar un nuevo hecho.  
- **Precondiciones:** El usuario debe estar autenticado y debe haber ingresado a la gestión de hechos.   
---

## Camino Principal

1. El usuario clickea el botón “Registrar hecho”.
2. El sistema solicita el nombre del hecho.
3. El usuario ingresa el nombre.
4. El sistema valida el hecho.
5. El sistema registra el hecho y le asigna un ID.

---

## Caminos Alternativos

X.2. Cancelación del usuario:**  
  El usuario puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú de gestión de hechos.

4.2 Hecho existente:**  
  Si el hecho ingresado ya existe, el sistema informa la duplicación y retorna al paso 3 para que el usuario ingrese un nuevo nombre.

--- 

- **Postcondición:** Hecho registrado.
