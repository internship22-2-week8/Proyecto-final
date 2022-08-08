# PROYECTO FINAL - PASANTIA 22.2

Se desea administrar las citas, especialistas, pacientes, personal y demas datos de 
la clinica de odontologia (¨nombre de la clinica¨).

De acuerdo a las entrevistas realizadas al personal y analisis de la información obtenida se lista lo siguiente.

## Requerimientos Funcionales:

## Gestion de Personal y Especialistas(Usuarios).


1.  Registro de los Especialistas: En este proceso se realizarán los registros de cada Especialista que preste servicios de salud para que quede registrado en el sistema. Los datos que se deben registrar son el Rut del especialista, Nombres, Apellidos y especialidad, además de una clave secreta, con la cual podrá tener acceso al sistema.

    Entrada: Ingreso de Rut, Nombres, Apellidos, Especialidad y clave secreta del especialista.

    Salida: El éxito de la operación será reflejado en el registro de los datos del especialista en el Sistema.

2. Modificación de Especialistas: Este proceso modifica uno o más datos de los especialistas que están almacenados en el Sistema, a excepción del Rut.

    Entrada: Ingreso de los datos a modificar, los cuales podrán ser: Nombres, Apellido Paterno, Apellido Materno o clave secreta.

    Salida: El éxito de la operación será la actualización de los datos en el Sistema.

3. Eliminación de Especialistas: Este proceso se lleva a cabo cuando un especialista deja de pertenecer al Departamento de Salud.

    Entrada: Ingreso del Rut del especialista.

    Salida: El éxito de la operación será reflejado la eliminación lógica o física del especialista en el Sistema.

---

4.  Registro de Secretarias: En este proceso se realizarán los registros de cada secretaria que preste los servicios de reserva de horas y creación de fichas clínicas para que ellas queden registradas en el sistema. Los datos que se deben registrar son el Rut de la secretaria, Nombres y Apellido Paterno y Materno, además de una clave secreta, con la cual podrá tener acceso al sistema.

    Entrada: Ingreso de Rut, Nombres, Apellido Paterno, Apellido Materno y clave secreta de la secretaria.

    Salida: El éxito de la operación será reflejado en el registro de los datos de la secretaria en el Sistema.

5.  Modificación de Secretarias: Este proceso modifica uno o más datos de las secretarias que están almacenados en el Sistema, a excepción del Rut.

    Entrada: Ingreso de los datos a modificar, los cuales podrán ser: Nombres, Apellido Paterno, Apellido Materno o clave secreta.

    Salida: El éxito de la operación será la actualización de los datos en el Sistema.


6. Eliminación de Secretarias: Este proceso se lleva a cabo cuando una secretaria deja de pertenecer al Departamento de Salud.

    Entrada: Ingreso del Rut de la secretaria.

    Salida: El éxito de la operación será reflejado en la eliminación lógica o física de la secretaria en el Sistema.

---

7. Registro de Asistentes: En este proceso se realizarán los registros de cada asistente que tengan los especialistas que prestan servicios de salud. Los datos que se deben registrar son el Rut del asistente, Nombres, Apellido Paterno, Apellido Materno y una clave secreta, con la cual podrá tener acceso al sistema.

    Entrada: Ingreso de Rut, Nombres, Apellido Paterno, Apellido Materno y clave secreta del asistente.

    Salida: El éxito de la operación será reflejado en el registro de los datos del asistente en el Sistema.

8. Modificación de Asistentes: Este proceso modifica uno o más datos de los asistentes que están almacenados en el Sistema, a excepción del Rut.

    Entrada: Ingreso de los datos a modificar, los cuales podrán ser: Nombres, Apellido Paterno, Apellido Materno o clave secreta.

    Salida: El éxito de la operación será la actualización de los datos en el Sistema.

7. Eliminación de Asistentes: Este proceso se lleva a cabo cuando un asistente deja de pertenecer al Departamento de Salud.

Entrada: Ingreso del Rut del asistente.

Salida: El éxito de la operación será reflejado la eliminación lógica o física del asistente en el Sistema.

## Gestion de pacientes

8. Ingreso de los datos personales del Paciente: Este es el proceso en el cual se ingresaran los datos personales del paciente que será atendido por primera vez en el Departamento de Salud, para que posteriormente adjuntarlo a la ficha clínica que tendrá el profesional que lo atenderá para que queden almacenados en el sistema. Al momento de llegar el paciente al departamento, para ser atendido, este deberá entregar a la secretaria sus datos personales, tales como Rut, Nombres, Apellido Paterno, Apellido Materno, Fecha de Nacimiento, Edad, Carrera, Año de Ingreso, Domicilio, Fono y Previsión.

  Entrada: Ingreso del Rut, Nombres del Alumno, Apellido Paterno, Apellido Materno, Fecha de Nacimiento, Edad, Carrera, Año de Ingreso, Domicilio, Fono y Previsión.

  Salida: El éxito de la operación será la existencia de la nueva ficha clínica en el Sistema.


9. Modificación de Pacientes: Este proceso modifica uno o más datos generales de los pacientes, a excepción del Rut, que cuentan con una ficha clínica existente en el sistema.

  Entrada: Ingreso de los datos a modificar, los cuales podrán ser: Nombres, Apellido Paterno, Apellido Materno, Domicilio, Carrera, Año de ingreso, Edad.

  Salida: El éxito de la operación será la actualización de los datos en el Sistema.




## Gestion de Reservaciones

10. Registro de Reservas de Horas: Este es el proceso en el cual se registrarán los datos necesarios para llevar a cabo de forma correcta la reserva de las horas. Estos datos corresponden a la Fecha de Reserva, Hora de Reserva, Nombres y Apellidos del Paciente, Nombres y Apellidos del Profesional que dará el servicio.

    Entrada: Ingreso de la Fecha de Reserva, Hora de Reserva, Nombres del Paciente, Apellidos Paterno y Materno de Paciente, Nombres del Profesional y Apellidos Paterno y Materno del Profesional que dará el servicio.

    Salida: El éxito de la operación será el registro de los datos en el Sistema.



## Expediente Clinica:
11. Consulta y edición de Fichas Clínicas: La consulta consiste en la recuperación de la ficha de un paciente en el momento que reciba algún servicio medico en el departamento de Salud, siempre y cuando este paciente ya cuente con una ficha clínica. Para ello se deberá ingresar el Rut del paciente del cual se pretende recuperar la ficha clínica junto con el nombre del profesional.

El campo Nombre del profesional será ingresado con anterioridad a la base de datos, para que posteriormente estos sean desplegados en pantalla a través de un combo.

  Entrada: Ingreso del Rut del paciente, nombre del profesional.

  Salida: El éxito de la operación consiste en la visualización de la ficha clínica del paciente con la información que tiene en dicha especialidad con el respectivo especialista.
  La edición consiste en registrar los diagnósticos, tratamientos, observaciones e indicaciones a las que será sometido el paciente por el profesional, junto con la fecha y hora que será atendido. Específicamente los campos son:
- Ficha para el dentista:
- Fecha.
- Hora.
- Tipo de Atención.(en el caso que sea urgencia)
- Pieza que será tratada.
- Superficie.
- Tipo de diagnóstico.
- Tratamientos indicados.
- Fecha de Reserva.
- Hora de Reserva.
- Tratamientos realizados.
- Indicaciones.
- Observaciones.
- Nombre del profesional.
- Estado de boletas.
- Estado de asistencias.

Los datos que contendrán los campos Tipo de diagnóstico, Tratamiento indicado, Tratamiento realizado y Nombre del profesional, deberán ser ingresados con anterioridad a la base de datos para que sean desplegados en pantalla a través de un combo y ser mantenidos con posterioridad. Los siguientes campos serán ingresados por código dentro del sistema, ya que no necesitarán una mantención posterior, estos son: Tipo de atención (Urgencia ó Tratamiento), Superficie (M, O ó D), Estado de boleta (Cancelado ó No Cancelado), Estado de asistencia (Asistió, No Asistió o atrasado). Por último los campos Indicaciones y Observaciones serán ingresados por el Profesional o asistente al sistema, como un campo memo.

Entrada: Cuando el paciente concurra al dentista, se ingresarán los datos, fecha, hora, número de pieza, superficie, tipo de diagnóstico, tratamiento indicado, presupuesto, nombre del profesional, fecha y hora de la próxima visita. Cuando el paciente va a realizar su tratamiento odontológico, el profesional ingresará los siguientes datos: estado de asistencia, tratamiento realizado, indicaciones, observaciones, estado de boleta, fecha y hora de la próxima visita al profesional.

Salida: El éxito de la operación consiste en el registro de las acciones realizadas por el profesional, tales como diagnóstico, tratamientos, tipo de pieza y superficie tratadas, Indicaciones, observaciones, profesional que realizo la transacción, estado de asistencia y boleta del paciente, fecha y hora de realización y posterior reserva de fecha y hora que quedaran ingresadas en el sistema.



12. Ingreso de los datos a ser mantenidos: Este proceso será el encargado de recibir los nombres que el profesional querrá que se desplieguen en pantalla, los cuales se dividirán en dos grupos:
· Ingreso a la base de datos, por tablas:
o Tipo de diagnósticos
o Tratamiento indicado
o Tratamientos

· Ingreso a través de código del sistema:
o Estado de boleta
o Estado de asistencia
o Superficie
o Tipo de atención
o Pieza

Los cuales se ingresaran uno a uno, según nombre ó código que especifique el profesional.

  Entrada: Ingreso del nombre del Tipo de diagnóstico o Tratamiento indicado o Tratamiento realizado o Nombre del profesional.

  Salida: El éxito de la operación será despliegue en pantalla de los datos anteriormente nombrados.


13. Registro de Estado de Asistencia por Paciente: Este proceso generará un duplicado del registro de la reserva de hora que hizo el paciente y lo traspasará a una tabla con el nombre de No_ asistio cuando el paciente no halla asistido a la consulta del profesional, si el paciente llega atrasado a la consulta este registro solamente se copiará a la tabla de Atrasos. Este proceso no afectará en ningún caso a los pacientes que tengan la opción de Asistió en su estado de asistencia.

  Entrada: Ingreso a la ficha clínica del paciente su estado de asistencia.

  Salida: Traspaso de los datos del paciente a las tablas correspondientes y posteriormente borrado de la ficha clínica según corresponda la transacción.

## Reportes

14. Personas Atendidas por Rango de fecha: Este proceso consiste en una consulta que entrega como resultado el número de personas atendidas entre el rango de fechas indicadas y por un especialista específico. Para ello se debe ingresar la fecha completa por la cual se desea consultar y la clave del especialista.

  Entrada: Ingreso de la fecha de Inicio y fecha de término por la cual se desea consultar.

  Salida: El éxito de la operación consiste en la visualización del número de personas atendidas.


15. Número de inasistencias Por Rango de fecha: Esta proceso consiste en una consulta que entrega el número de inasistencias a horas reservadas que se producen en un rango de fecha indicado para un especialista en particular. Para ello se debe ingresar la fecha completa por la cual se desea consultar

  Entrada: Ingreso de la fecha de inicio y la fecha de término, por la cual se desea consultar.

  Salida: El éxito de la operación consiste en la visualización del número de inasistencias a horas por el rango de fecha.

16. Número de inasistencias por Paciente: Este proceso consiste en una consulta que entrega el número de inasistencias a horas reservadas que se producen por un mismo paciente a un mismo especialista. Para ello se debe ingresar el Rut del paciente.

  Entrada: Ingreso del Rut del paciente.

  Salida: El éxito de la operación consiste en la visualización del número de inasistencias de horas reservadas por un paciente en particular para un mismo especialista.

17. Número de Atrasos Por Rango de fecha: Esta proceso consiste en una consulta que entrega el número de atrasos en las horas reservadas que se producen en un rango de fecha indicado, para un especialista en particular. Para ello se debe ingresar la fecha completa por la cual se desea consultar.

  Entrada: Ingreso de la fecha de inicio y fecha de termino por la cual se desea consultar.

  Salida: El éxito de la operación consiste en la visualización del número de atrasos en las horas reservadas por el rango de fecha.

18. Número de Atrasos por Paciente: Este proceso consiste en una consulta que entrega el número de atrasos a horas reservadas que se producen por un mismo paciente a un mismo especialista. Para ello se debe ingresar el Rut del paciente y la clave del especialista.

  Entrada: Ingreso del Rut del paciente y la clave del especialista.

  Salida: El éxito de la operación consiste en la visualización del número de atrasos en las horas reservadas por un paciente en particular para un mismo especialista.

## Desarrollo del sistema:

Como desarrollador se le pide, realizar lo siguiente:

- Documento de diseño del proyecto.
- Diagrama de clases.
- Prototipo del proyecto (no se tiene restricciones).
- Desarrollo del Backend (API-rest con Django y djangorestframework)
- Desarrollo del Frontend (SPA con reactjs)
- Implementar Redux en los estados que considere pertinente.
- Agregar los modulos necesarios que no estan descritos en los requerimientos funcionales.
# Proyecto-final
