
# Libro de sumarios virtual

**Institución:** ISPI 4038 - Juan Pablo II  
**Carrera:** Técnico Superior en Desarrollo de Software  
**Materia:** Práctica profesionalizante II 
**Alumno:** Ignacio Fleita  
**Profesor:** Sebastian Bruselario
**Lugar:** Roldán, Santa Fe  

---

## Introducción

Este software está diseñado para transformar el manejo del libro de sumarios de una comisaría mediante su digitalización. Su implementación permitirá una gestión más ágil y eficiente de los datos, abordando varios problemas actuales.

Uno de los problemas que el software resolverá es la presentación de denuncias. En lugar de tener que entregarlas físicamente en la fiscalía, el jefe de sumario podrá enviarlas por correo electrónico, simplificando el proceso y aumentando la accesibilidad.

Otro aspecto clave es la búsqueda de información. En el sistema actual, la revisión de las denuncias se realiza manualmente, hoja por hoja, lo cual es lento y propenso a errores. Con el nuevo software, será posible buscar denuncias por fecha, número de denuncia, tipo de hecho y otros criterios relevantes, haciendo que la búsqueda sea rápida y precisa.

En definitiva, este software mejorará la eficiencia operativa en la comisaría y ofrecerá una experiencia más conveniente para los policías, modernizando y agilizando los procesos de gestión de denuncias.

---

## Virtual summary book

### Introduction

This software is designed to transform the management of a police station's summary book through its digitization. Its implementation will allow more agile and efficient data management, addressing several current problems.

One of the problems that the software will solve is the filing of complaints. Instead of having to physically deliver them to the prosecutor's office, the head of the investigation will be able to send them by email, simplifying the process and increasing accessibility.

Another key aspect is the search for information. In the current system, review of complaints is done manually, sheet by sheet, which is slow and error-prone. With the new software, it will be possible to search for complaints by date, complaint number, type of event and other relevant criteria, making the search quick and accurate.

Ultimately, this software will improve operational efficiency at the police station and offer a more convenient experience for police officers, modernizing and streamlining complaint management processes.

---

## Requerimientos generales

- Gestión de denuncias  
- Gestión de hechos  
- Gestión de sumariantes  

## Requerimientos específicos

### Gestión de hechos:

- Registrar hecho con id y nombre  
- Modificar hecho  
- Eliminar hecho  

### Gestión de sumariantes:

- Registrar sumariante con nombre, apellido y número identificatorio  
- Modificar sumariante  
- Listar sumariantes  
- Eliminar sumariante  
- Consultar sumariante  
- (Cuando el usuario intenta ingresar al menú de gestión de sumariantes, el sistema le solicitará usuario y contraseña de administrador)

### Gestión de denuncias: 

- Registrar denuncia con número de denuncia, fecha, nombre de la víctima, nombre del imputado (si hubiera), lugar del hecho, causa, detenidos (sí/no), fiscalía/juzgado, observaciones, número de elevación del sumario al fiscal, la fecha de la elevación, complemento (si se elevara más de una vez) y el nombre del sumariante  
- Agregar complemento  
- Modificar fecha de elevación  
- Registrar modificación con fecha y hora, nombre y apellido del sumariante  

---

## PANTALLAS

### Pantalla inicio

### Pantalla sesión iniciada

---

## GESTIÓN DE SUMARIANTES

### REGISTRAR SUMARIANTE

**Caso de Uso:** Registrar Sumariante  
**Actor Principal:** Administrador  
**Descripción:** Permite al administrador registrar un nuevo sumariante en el sistema.  
**Precondiciones:** Debe ingresar con credenciales de administrador.

**Flujo:**

1. Clic en “agregar sumariante”  
2. El sistema solicita número identificatorio, nombre y apellido  
3. El administrador ingresa los datos  
4. El sistema valida y registra al sumariante  
5. Si hay campos inválidos, vuelve al paso 3  
6. Confirmación de registro exitoso

---

### MODIFICAR SUMARIANTE

**Caso de Uso:** Modificar Sumariante  
**Actor Principal:** Administrador  
**Precondiciones:** Debe estar autenticado y haber consultado al sumariante previamente.

**Flujo:**

1. Seleccionar sumariante → clic en “modificar sumariante”  
2. El sistema muestra los datos  
3. El administrador modifica los datos  
4. Validación y actualización  
5. Si hay datos inválidos, vuelve al paso anterior  
6. Confirmación de modificación

---

### ELIMINAR SUMARIANTE

**Caso de Uso:** Eliminar Sumariante  
**Actor Principal:** Administrador  
**Precondiciones:** Debe estar autenticado.

**Flujo:**

1. Seleccionar sumariante → clic en “eliminar”  
2. Confirmación de eliminación  
3. Confirmar o cancelar  
4. Eliminación exitosa

---

## GESTIÓN DE HECHOS

### REGISTRAR HECHO

**Caso de Uso:** Registrar Hecho  
**Actor Principal:** Sumariante  
**Flujo:**

1. Clic en “Registrar hecho”  
2. Ingresar nombre del hecho  
3. Validación  
4. Registro exitoso con asignación de ID  

---

### MODIFICAR HECHO

**Actor Principal:** Usuario  
**Precondiciones:** Debe estar autenticado.

**Flujo:**

1. Selección del hecho  
2. Clic en “modificar hecho”  
3. Ingreso de nuevos datos  
4. Validación y actualización  
5. Confirmación

---

## GESTIÓN DE DENUNCIAS

### REGISTRAR DENUNCIA

**Actor Principal:** Usuario  
**Precondiciones:** Autenticado

**Flujo:**

1. Clic en “Nueva denuncia”  
2. Completar formulario  
3. Validación  
4. Confirmación y registro con ID  

---

### MODIFICAR DENUNCIA / AGREGAR COMPLEMENTO

**Actor Principal:** Usuario  
**Precondiciones:** Denuncia ya registrada y filtrada

**Flujo:**

1. Selección de denuncia → clic en “Modificar”  
2. Clic en “agregar elevación”  
3. Confirmar o cancelar  
4. Registro de número y fecha de elevación  

---

## Entrevista

- **¿Cuál es el propósito principal del software?**  
  Digitalizar el libro de sumarios

- **¿Con qué dispositivo cuentan para utilizar el software?**  
  Computadora

- **¿El lugar cuenta con conexión a internet?**  
  Sí

- **¿Qué información de cada denuncia quedaría registrada en el sistema?**  
  Fecha, Número de denuncia, nombre del denunciante, nombre del imputado, detalles del hecho, tipo de delito, fecha y número de elevación, observaciones y lugar del hecho

- **¿Sería útil agregar un listado de hechos?**  
  Sí. Robo, hurto, amenaza, lesiones culposas en accidentes de tránsito, lesiones dolosas, amenazas calificadas, robo calificado.

- **¿La información quedaría en el sistema o se elevaría?**  
  Ambas

- **¿Cómo se eleva? ¿Por qué puede elevarse más de una vez?**  
  Se envían fotocopias. Puede haber novedades → complemento

- **¿El software necesitará autenticación de usuarios?**  
  No

- **¿Qué datos deben ingresar?**  
  Nombre, apellido, número identificatorio

- **¿Funcionalidades específicas?**  
  Filtrado por cualquier dato

- **¿Qué procesos actuales solucionaría?**  
  Agilidad en búsqueda y envío de datos
