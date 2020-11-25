# useForm custom hook

```
const initialForm = {
    name: 'Cristian',
    lastname: 'Sulbaran',
    email: 'cristian.example@example.com'
}

const  [ value, handleInputChange, reset ] = useForm(initialForm);
```

El valor por defecto del useForm es un objeto vacío por lo que procuramos insertar un objeto con las key/values necesarias para nuestra form, que utilizaremos como por ejemplo cuando queramos conseguir valores de un formulario grande, y necesitemos enviarlo a un servidor para ser procesado.

*value* //valor actual del estado de nuestro initialForm

*handleInputChange({e.target})* // modifica el e.target.value del e.target.name y devuelve el nuevo estado, actualizado.

*reset()* // Modifica todo el estado actual a sus valores iniciales.