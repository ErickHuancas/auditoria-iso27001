REPORTE DE AUDITORÍA DE PERMISOS
Objetivo

Verificar los permisos de acceso de los archivos confidenciales de la empresa.

Hallazgo

Se identificaron permisos 777 en los archivos planilla.xlsx y empleados.csv.

Incumplimiento

Los permisos 777 permiten que todos los usuarios puedan leer, escribir y ejecutar los archivos, generando una exposición innecesaria de información confidencial.

Riesgos identificados
Acceso no autorizado.
Modificación de información.
Divulgación de datos personales.
Pérdida de integridad de los archivos.
Control ISO 27001
A.5.15: Control de acceso.
A.5.18: Derechos de acceso.
A.8.3: Restricción de acceso a la información.
Acción correctiva

Se modificaron los permisos utilizando chmod 640 para limitar el acceso.

Conclusión

La corrección de permisos permite mejorar la protección de los activos de información y reducir el riesgo de accesos no autorizados.
