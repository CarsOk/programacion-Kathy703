# Diciembre 5 del 2021

# Ejercicio 1

## Ejercicios de practica

- Hacer que mi nombre o cualquier palabra se mueva horizontal por las columnas de excel
utilizando el ciclo while.

### Ejercicio en excel:

```
Sub prueba()

 i = 1
 s = "katy"

  While i <= 8
   mus.Cells(3, i) = ""
   mus.Cells(3, i) = s
   MsgBox "listo"
   i = i + 1
   mus.Cells(3, i - 1) = ""
   Wend

End Sub
```

# Ejercicio 2

- Hacer que cualquier palabra se mueva de forma vertical por las filas de excel utilizando el ciclo while.

### Ejercicio en excel:


```
Sub prueba()

 i = 4
 s = "katy"

  While i <= 9
   mus.Cells(i - 1, 4) = ""
   mus.Cells(i, 4) = s
   MsgBox "listo"
   i = i + 1
   mus.Cells(i - 1, 4) = ""
   Wend

End Sub
```
