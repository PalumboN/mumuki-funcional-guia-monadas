No debería soprendernos que muchos tipos de datos, como la lista y el maybe también cumplan esta interfaz. Usando la consola, ¡descubrí que hace el `>>=` con estos tipos datos!

Te dejamos las siguientes funciones ya hechas para usar en tus pruebas:

```haskell
inversa 0 = Nothing
inversa x = Just (1 / x)
```

```haskell
menoresA n = [0..n]
```