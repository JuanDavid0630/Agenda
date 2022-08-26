# Agenda

[Hoja de vida](https://github.com/JuanDavid0630/Hoja-de-vida-.git)

# Dia 12/08/22
"Programacion en Visual Basic"
```
Sub Sena()
 Nom = "Luis"
 MsgBox Nom
 Num = 10
 MsgBox Num
 Nom = "Maria"
 MsgBox "El nombre es: " & Nom
End Sub
```
## Taller visual basic   Dia 26/08/22
```
Sub Inicio()
    f1 = InputBox("Ingrese Ingresos anuales")
     If f1 < 1000 Then
     MsgBox ("No se paga impuesto")
     
     Else
        If f1 >= 1001 And f1 < 10000 Then
        impuesto = 0.05
        MsgBox ("el pago anual es:") & f1 * impuesto
        Else
            If f1 >= 10001 And f1 < 100000 Then
            impuesto = 0.1
            MsgBox ("el pago anual es") & f1 * impuesto
            Else
                If f1 >= 100001 And f1 < 1000000 Then
                 impuesto = 0.15
                 MsgBox ("el pago anual es:") & f1 * impuesto
                Else
                     If f1 >= 10000001 And f1 < 10000000 Then
                     impuesto = 0.2
                     MsgBox ("el pago anual es:") & f1 * impuesto
                     Else
                        If f1 >= 10000001 Then
                        impuesto = 0.25
                        MsgBox ("el pago anual es:") & f1 * impuesto
                        End If
                     End If
                End If
            End If
        End If
    End If 
End Sub
```
