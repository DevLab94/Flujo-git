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