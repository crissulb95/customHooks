# useFetch custom hook

```
const url = `https://www.ejemplo.com/api/endpoint`;
const { 
        data: null,
        loading: true,
        error: null,
    };
```


useFetch(url) // Acepta un parámetro url para iniciar un fetch y devolver como resultado un objeto con las 3 propiedades descritas arriba, según lo que haya podido extraer el hook de la url ingresada