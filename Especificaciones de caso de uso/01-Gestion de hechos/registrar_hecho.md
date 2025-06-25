# REGISTRAR HECHO

- **Caso de Uso:** Registrar Hecho  
- **Actor Principal:** Sumariante  
- **Descripción:** Permite al sumariante registrar un nuevo hecho.  
- **Precondiciones:** Debe haber ingresado a la gestión de hechos  

| Paso Principal                                                                 | Alternativa                                                                 |
|--------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| 1. El usuario clickea el botón “Registrar hecho”                              | 1.2 El usuario puede cancelar la acción en cualquier momento                |
| 2. El sistema solicita el nombre del hecho                                    |                                                                              |
| 3. El usuario ingresa el nombre                                               |                                                                              |
| 4. El sistema valida el hecho                                                 | 4.2 Hecho existente, el sistema lo lleva de nuevo al paso 3                 |
| 5. El sistema registra el hecho y le asigna un id                             |                                                                              |

- **Postcondición:** El sistema confirma el registro exitoso
