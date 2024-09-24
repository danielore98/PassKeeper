# Proyecto de gestión de contraseñas "PassKeeper"
## Descripción
Desarrolla una herramienta para que los usuarios puedan almacenar y gestionar sus contraseñas de forma segura. El proyecto debe implementar las funcionalidades básicas de añadir, editar y eliminar contraseñas, asegurando la protección de los datos con una base de datos SQLite y empleando contenedores Docker para gestionar el entorno de desarrollo.
## Equipo de desarrollo
| Apellidos y nombres | Rol |
|---------------------|-----|
| Ore Campos, Daniel Leonardo | Scrum master |
| Escobar Bendezu, Aldrin | Product Owner |
| Boza More, Luis Eduardo | Product Owner |

## Historia de Usuario
| Identificador | E001 |
|---------------------|-----|
| Nombre (alias) | Login |
| Descripción | Yo como cliente , necesito acceso al sistema , con la finalidad de realizar mis pedidos. |
| Nombre (alias) | Login |
| Puntos de historia (días ideales) | 2 |
| Criterios de aceptación | En caso que el cliente este registrado y adicionalmente recuerda su nombre de usuario y contraseña, cuando accede al sistema, el sistema le muestra la pantalla de bienvenida. |
| ------- | En caso que el cliente no esta registrado, cuando accede al sistema, el sistema lepresenta las opciones de registrarse. |


## Historia de Usuario
| Identificador | H001 |
|---------------------|-----|
| Nombre (alias) | Guardar Contraseña |
| Descripción | Yo como usuario, necesito guardar mis contraseñas en un lugar seguro, con la finalidad de acceder a mis cuentas cuando lo necesite. |
| Puntos de historia (días ideales) | 3 |
| Criterios de aceptación | En caso de que el usuario ingrese una contraseña válida, el sistema la almacena de manera cifrada y le notifica que se ha guardado correctamente. |
| ------- | En caso de que la contraseña no cumpla con los requisitos de seguridad, el sistema muestra un mensaje de error y solicita una nueva contraseña. |

---

## Historia de Usuario
| Identificador | H002 |
|---------------------|-----|
| Nombre (alias) | Editar Contraseña |
| Descripción | Yo como usuario, necesito editar mis contraseñas almacenadas, con la finalidad de mantenerlas actualizadas cuando cambie alguna. |
| Puntos de historia (días ideales) | 4 |
| Criterios de aceptación | En caso de que el usuario seleccione una contraseña para editar, el sistema le permite modificarla y guarda los cambios de manera segura. |
| ------- | En caso de que el usuario intente editar una contraseña con requisitos inválidos, el sistema muestra un mensaje de error. |

---

## Historia de Usuario
| Identificador | H003 |
|---------------------|-----|
| Nombre (alias) | Buscar Contraseña |
| Descripción | Yo como usuario, necesito buscar una contraseña específica en mi lista, con la finalidad de acceder rápidamente a mis cuentas. |
| Puntos de historia (días ideales) | 2 |
| Criterios de aceptación | En caso de que el usuario ingrese el nombre de la cuenta, el sistema muestra la contraseña correspondiente en la lista. |
| ------- | En caso de que la cuenta no exista, el sistema muestra un mensaje indicando que no se encontró ninguna coincidencia. |

---

## Historia de Usuario
| Identificador | H004 |
|---------------------|-----|
| Nombre (alias) | Eliminar Contraseña |
| Descripción | Yo como usuario, necesito eliminar contraseñas que ya no utilizo, con la finalidad de mantener mi gestor de contraseñas organizado. |
| Puntos de historia (días ideales) | 2 |
| Criterios de aceptación | En caso de que el usuario seleccione una contraseña para eliminar, el sistema solicita confirmación y, al confirmar, elimina la contraseña de manera segura. |
| ------- | En caso de que el usuario cancele la eliminación, el sistema no realiza ningún cambio. |

---

## Historia de Usuario
| Identificador | H005 |
|---------------------|-----|
| Nombre (alias) | Generar Contraseña |
| Descripción | Yo como usuario, necesito que el sistema genere contraseñas seguras automáticamente, con la finalidad de usarlas en mis cuentas. |
| Puntos de historia (días ideales) | 3 |
| Criterios de aceptación | En caso de que el usuario solicite una nueva contraseña, el sistema genera una contraseña aleatoria que cumple con los criterios de seguridad y la presenta al usuario. |
| ------- | En caso de que el usuario no esté satisfecho con la contraseña generada, puede solicitar otra hasta que esté conforme. |

---

## Historia de Usuario
| Identificador | H006 |
|---------------------|-----|
| Nombre (alias) | Copia de Seguridad |
| Descripción | Yo como usuario, necesito realizar copias de seguridad de mis contraseñas, con la finalidad de no perder la información en caso de fallo del sistema. |
| Puntos de historia (días ideales) | 5 |
| Criterios de aceptación | En caso de que el usuario inicie el proceso de copia de seguridad, el sistema crea un archivo cifrado con todas las contraseñas almacenadas y lo guarda en el dispositivo del usuario. |
| ------- | En caso de que la copia de seguridad falle, el sistema muestra un mensaje de error y solicita que se intente nuevamente. |
