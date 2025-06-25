# Caso de Uso: Registrar Sumariante

- **Actor Principal:** Administrador  
- **Descripción:** Permite al administrador registrar un nuevo sumariante en el sistema.  
- **Precondiciones:** El usuario deberá ingresar al módulo "Gestionar Sumariante" con credenciales de administrador otorgadas previamente por el desarrollador del software.  

---

## Camino Principal

1. El administrador clickea el botón “Agregar sumariante”.
2. El sistema solicita número identificatorio del sumariante, nombre y apellido.
3. El administrador ingresa los datos.
4. El sistema valida la información y registra al sumariante.

---

## Caminos Alternativos

X.2 Cancelación del administrador:**  
  El administrador puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

4.2 Campos incompletos o no válidos:**  
  El sistema detecta errores o campos vacíos y lo lleva nuevamente al paso 3 para corregir los datos.

---

- **Postcondición:** El sistema confirma el registro exitoso.
