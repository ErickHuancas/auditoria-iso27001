INFORME DE HALLAZGOS DE AUDITORÍA
Objetivo

Identificar las no conformidades relacionadas con la seguridad de la información y proponer acciones correctivas.

Hallazgo 1: Contraseñas compartidas

Evidencia: Se identificó que varios trabajadores utilizan una misma contraseña para acceder a los sistemas de la empresa.

Riesgo: Acceso no autorizado, pérdida de trazabilidad y dificultad para identificar al responsable de una actividad.

Recomendación: Implementar cuentas individuales, contraseñas personales y autenticación multifactor.

Hallazgo 2: Archivos sensibles con permisos 777

Evidencia: Los archivos planilla.xlsx y empleados.csv tenían permisos 777, permitiendo que cualquier usuario pudiera leer, modificar y ejecutar los archivos.

Riesgo: Exposición de información confidencial, modificación no autorizada y pérdida de integridad de los datos.

Recomendación: Aplicar el principio de mínimo privilegio y establecer permisos adecuados mediante chmod 640.

Hallazgo 3: Usuarios inactivos sin eliminar

Evidencia: Se identificaron cuentas de usuarios que ya no trabajan en la empresa y que todavía permanecen habilitadas.

Riesgo: Estas cuentas pueden ser utilizadas para acceder a información sin autorización, aumentando la posibilidad de incidentes de seguridad.

Recomendación: Implementar revisiones periódicas de usuarios, deshabilitar cuentas inactivas y retirar los accesos cuando finalice la relación laboral.

Conclusión general

La auditoría permitió identificar tres situaciones que afectan la seguridad de la información de la empresa.

Se recomienda fortalecer los controles de acceso, establecer políticas de contraseñas, revisar periódicamente las cuentas de usuario y aplicar el principio de mínimo privilegio para proteger los activos de información.

Referencia normativa

ISO/IEC 27001:2022, Anexo A:

A.5.15: Control de acceso.
A.5.16: Gestión de identidades.
A.5.18: Derechos de acceso.
A.5.17: Información de autenticación.
A.8.3: Restricción de acceso a la información.
