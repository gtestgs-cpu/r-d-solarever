# Investigación y Desarrollo · Grupo Solarever

Repositorio del Departamento de Investigación y Desarrollo (I+D) de Grupo Solarever, S.A. de C.V. Contiene las páginas públicas que se integran con la App I+D (Google Apps Script).

| Carpeta | Contenido | Enlace |
|---|---|---|
| `sondeo/` | Formulario de Sondeo a Clientes (GS-ID-RG-01) para Ventas, Soporte Técnico y otras áreas. Requiere el código de acceso que define I+D en la App I+D. | https://gtestgs-cpu.github.io/r-d-solarever/sondeo/ |
| `recursos/` | Logotipos e iconos de la marca Solarever usados por las páginas y por la App I+D. | — |

## Funcionamiento

- Las páginas no almacenan información: los datos se envían directamente a la App I+D, que los guarda en su base de datos.
- La dirección de la App I+D se configura en `sondeo/index.html` (variable `API_URL`) con la URL de la implementación que termina en `/exec`.
- El código de acceso del formulario se define y se cambia en la App I+D: **Administración → Configuración**.

Documento de referencia: Manual GS-ID-MA-04 de la Aplicación Web de I+D.
