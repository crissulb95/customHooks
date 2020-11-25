# useCounter custom hook

```
const { Counter, increment, decrement, reset } = useCounter(4);
```

useCounter() //recibe un valor por defecto pero tiene un valor predeterminado de 10

increment y decrement // suman o restan por 1 el valor actual del estado en el useCounter

reset // devuelve el numero a su estado inicializado dentro del useCounter -> en este caso, 4