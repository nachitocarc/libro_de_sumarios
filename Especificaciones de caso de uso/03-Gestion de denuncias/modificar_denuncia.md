# Caso de Uso: Modificar denuncia / Agregar complemento

- **Actor Principal:** Usuario  
- **Descripción:** Permite al usuario agregar una primera o una nueva elevación.  
- **Precondiciones:** El usuario debe estar autenticado y haber filtrado una denuncia.  

---

## Camino Principal

1. El usuario selecciona la denuncia y clickea el botón “Modificar”.
2. El sistema muestra todos los datos de la denuncia y una sección de elevaciones.
3. El usuario clickea el botón “Agregar elevación”.
4. El sistema muestra un mensaje de confirmación.
5. El usuario acepta la confirmación.
6. El sistema agrega el número de elevación y la fecha de la misma.

---

## Caminos Alternativos

X.2 Cancelación del usuario:**  
  El usuario puede cancelar la acción en cualquier momento. El sistema detiene el proceso y vuelve al menú anterior.

4.2 Confirmación denegada:**  
  El usuario niega la confirmación y se cancela el agregado de la elevación.

---

- **Postcondición:** La elevación fue agregada con éxito.
