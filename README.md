# Gestión de usuarios en Linux

Este script facilita la gestión de usuarios en sistemas GNU/Linux. Susfunciones son la creación de usuarios, la modificación de contraseñas, la eliminación de usuarios y la incorporación de usuarios a grupos.

Debe ser ejecutado como superusuario (root).

Para descargarlo, podemos clonar el repositorio:

git clone https://github.com/DASOA-Linux/users

Acceder al directorio:

cd users/

Dar permiso de ejecución al script:

chmod +x user.sh

Y ejecutarlo:

./user.sh

__________________________________________________________________

Otra opción es descargar directamente el script:

wget https://github.com/DASOA-Linux/users/blob/main/user.sh


Dar permiso de ejecución al script:

chmod +x user.sh

Y ejecutarlo:

./user.sh

__________________________________________________________________


Funcionalidades

1. Crear un nuevo usuario:

Solicita el nombre del nuevo usuario.
Verifica si el nombre de usuario ya existe.
Permite establecer una contraseña para el nuevo usuario (opcional).

2. Modificar contraseña de un usuario:

Solicita el nombre del usuario.
Verifica si el usuario existe.
Permite cambiar la contraseña del usuario.

3. Eliminar un usuario:

Solicita el nombre del usuario a eliminar.
Verifica si el usuario existe.
Elimina el usuario y sus archivos asociados.

4. Añadir un usuario a un grupo:

Solicita el nombre del usuario.
Verifica si el usuario existe.
Solicita el nombre del grupo.
Verifica si el grupo existe.
Añade el usuario al grupo especificado.

5. Salir:

Finaliza la ejecución del script.

__________________________________________________________________


Notas:

En cada función que solicita información del usuario, se verifica la existencia del mismo antes de continuar para evitar errores.

El script proporciona mensajes de error descriptivos en caso de entrada incorrecta o acciones no válidas.


Desarrollado por:

DASOA Linux https://www.dasoa.net

Licencia:

Este proyecto está bajo la Licencia Pública General de GNU, versión 3.0 (GNU GPL v3.0). Consulta el archivo LICENSE para obtener más información.
