# Septiembre 13 del 2021

En la clase anterior el instructor nos mostro como se simboliza
una decision en el diagrama de flujo y tambien como se escribe una decision en
visual vasic y en dartpad.
Luego nos dio algunos ejemplos sencillos.

## Ejercicio en excel

```
Sub ejemplo()

  n = Int(InputBox("escriba un numero"))
  If (n > 10) Then
  MsgBox "el numero " & n & " es mayor que 10"
  Else
  MsgBox "el numero " & n & " es menor o igual a 10"
  End If

End Sub
```

## Ejercicio en dartpad

```
void main() {
  int n = 19;

  if (n > 10){
     print("el numero $n es mayor que 10");
 }else{
      print("el numero $n es menor o igual a 10");
  }
}
```

# Actividad de desarrollo

1.Hacer un programa de calcule el promedio de 5 notas y le muestre un
mensaje al usuario indicando si el estudiante gano o no la asignatura.

2.diagrama de flujo.

## Ejercicio en excel

```
Sub promedio()

   s1 = InputBox("primera nota")
   f2 = InputBox("segunda nota")
   r3 = InputBox("tercera nota")
   v4 = InputBox("cuarta nota")
   t5 = InputBox("quinta nota")
   x = Int(s1) + Int(f2) + Int(r3) + Int(v4) + Int(t5)
    MsgBox "el promedio es " & x / 5

       y = x / 5

    If (y > 6) Then
        MsgBox " el estudiante saco " & y & " aprobo"
    Else
        MsgBox "el estudiante saco " & y & " reprobo"
     End If

End Sub
```
