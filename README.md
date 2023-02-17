Las funciones de formulario y globales se escriben de la siguiente manera:

BizuitForm['NombreFuncion'] = async function (parametro1, parametro2, parametro n)
{
// código
}
Ejemplo:

BizuitForm['HolaMundo'] = async function(name)
{
    console.log(nombre);
}
Este código es invocado desde los controles de la siguiente manera:

BizuitForm.NombreFuncion(parametro1,parametro2, parametro n)

Ejemplo:

BizuitForm.HolaMundo("Juan Carlos");


New work item
