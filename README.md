# Flujo-Git
Documentacion  de glujo de trabajo remoto con GIT

## Organizacion
Se recomienda crear una organizacion que sea la propietaria del repositorio principal. A partir de dicho repositorio los miembros o colaboradores podran hacer un fork hacia sus cuentas personales.

### Pasos para crear una Organizacion

1. Hacer click en foto de perfil
2. Click en Settings
3. Click en Organizaciones
4. Click en Nueva Organizacion
5. Elegir plan y llenar datos


### Creacion del Fork

Para crear un Fork debes iniciar secion en Github y luego ingresar a la landing page del proyecto del que quieras sacar tu Fork.

## Como trabajar con 2 o mas remotos

Listar remotos
`git remote -v`

Agregar remotos
`git remote add Flujo-git https://github.com/DevLab94/Flujo-git.git`

Eliminar Remotos
`git remote remove Flujo-git`

## Creando etiquetas

Es necesario entender que las etiquetas(release) solo deben ser creadas a partir de la rama master como buena practica. 

Para entender como llamar o categorizar a tus versiones te recomendamos un articulo https://ed.team/blog/como-se-deciden-las-versiones-del-software


## PASOS A SEGUIR PARA TRABAJAR EN EQUIPO
1: Crear una Organizacion en GITHub (Esto lo hace el administrador del proyecto)
2: Crear un Proyecto dentro de la Organizacion (Esto lo hace el administrador del proyecto)
3: Si el Proyecto es privado, agregar a todos los colaboradores
4: Cada colaborador debe hacer un Fork del proyecto Original en su cuenta de GITHub
5: Cada desarrollador debe clonar su Fork en su PC
6: El desarrollador debe agregar los remotos correspondientes del proyecto Original
7: Se debe asegurar que todo este correctamente sincronizado
8: Se debe crear una nueva rama cada ves que vaya a trabajar una nueva funcionalidad
9: Una ves terminada la nueva funcionalidad, el desarrollador debe subir(push) esa rama al Fork de su cuenta
10: En GITHub le aparecera la opcion de crear un Pull Request
11: Una ves creado el Pull Request el administrador del proyecto lo revisara
12: Se aprueba o se rechaza el Pull request
13: Cada desarrollador debe revisar constantemente (fetch) si no hubo cambios en el proyecto original
14: Se debe eliminar las ramas que ya fueron aprobadas o rechazadas