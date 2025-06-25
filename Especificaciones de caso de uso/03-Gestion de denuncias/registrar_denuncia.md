# Caso de Uso: Registrar Denuncia

- **Actor Principal:** Usuario  
- **Descripción:** Permite al usuario agregar/registrar una nueva denuncia.  
- **Precondiciones:** El usuario debe estar autenticado.  

---

## Camino Principal

1. El usuario clickea el botón “Nueva denuncia”.
2. El sistema muestra un formulario con datos a completar.
3. El usuario rellena el formulario con los datos de la denuncia.
4. El sistema valida la denuncia.
5. El sistema solicita confirmación del registro de la denuncia.
6. El usuario confirma el registro.
7. El sistema registra la denuncia y le asigna un ID.

---

## Caminos Alternativos

X.2 Cancelación del usuario:**  
  El usuario puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

4.2 Datos incompletos:**  
  El sistema detecta que faltan campos obligatorios, informa al usuario y lo lleva nuevamente al paso 3 para completar los datos.

---

- **Postcondición:** La denuncia fue registrada con éxito.
