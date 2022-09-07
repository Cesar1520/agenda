# agenda
registro para actividades
cesar lopez.  ficha 2558427
---
## (hoja de vida)[https://github.com/Cesar1520/agenda.git]
## dia 12/08/22
### progrmacion visual basic
```
sub sena ()

nom = "luis"

msgbox num

nom = "maria"

msgbox "el nombre es" & nom

end sub
```
___
### trabajo 26 de agosto

```

    Sub impuesto()
        a = Int(InputBox("valor a pagar anual"))
        
        Total = a * ip
        
        If a > 0 And a < 1000 Then
        MsgBox " no pagar impuesto"
        
        Else
        If a > 1001 And 10000 Then
            ip = 0.05
            Total = a * ip
            
            MsgBox " el total es: " & Total
            
        Else
            If a > 10001 And a < 100000 Then
            ip = 0.1
            Total = a * ip
            
            MsgBox " el total es: " & Total
            
            Else
                If a > 100001 And a < 1000000 Then
                    ip = 0.15
                    Total = a * ip
                    
                    MsgBox " el total es: " & Total
                
                Else
                    If a > 1000001 And a < 10000000 Then
                    ip = 0.2
                    Total = a * ip
                    
                    MsgBox " el total es: " & Total
                        
                    Else
                    If a > 10000001 And a < 100000000 Then
                        ip = 0.25
                        Total = a * ip
                    
                    MsgBox " el total es: " & Total
                    
                    End If
                    End If
                End If
            End If
        End If
        End If
    End Sub

```

### Programa de impuesto con estructura Select Case

```
Sub sena()
    ingreso = Int(InputBox("Escriba los ingresos anuales de la empresa"))
        Select Case ingreso
            Case 0 To 1000
                MsgBox ("El impuesto a pagar es: " & ingreso)
                Case 1001 To 10000
                    impuesto = ((ingreso * 5) / 100)
                    MsgBox ("El impuesto a pagar es: " & impuesto)
                Case 10001 To 100000
                    impuesto = ((ingreso * 10) / 100)
                    MsgBox ("El impuesto a pagar es: " & impuesto)
                Case 100001 To 1000000
                    impuesto = ((ingreso * 15) / 100)
                    MsgBox ("El impuesto a pagar es: " & impuesto)
                Case 1000001 To 10000000
                    impuesto = ((ingreso * 20) / 100)
                    MsgBox ("El impuesto a pagar es: " & impuesto)
                Case Else
                    impuesto = ((ingreso * 25) / 100)
                    MsgBox ("El impuesto a pagar es: " & impuesto)
        End Select
End Sub
```

___
