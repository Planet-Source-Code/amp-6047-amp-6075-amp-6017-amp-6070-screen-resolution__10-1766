<div align="center">

## Screen Resolution


</div>

### Description

'This code will tell you how to get our computer screen resolution

'just a few lines of codes..
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[&amp;\#6047;&amp;\#6075;&amp;\#6017;&amp;\#6070;](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/amp-6047-amp-6075-amp-6017-amp-6070.md)
**Level**          |Beginner
**User Rating**    |4.3 (17 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__10-1.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/amp-6047-amp-6075-amp-6017-amp-6070-screen-resolution__10-1766/archive/master.zip)





### Source Code

```
'This code will tell you how to get our computer screen resolution
'just a few lines of codes..
  Private Sub Form1_Load(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles MyBase.Load
    Dim DeskTop As System.Windows.Forms.Screen
    Dim theWidth As Integer = DeskTop.PrimaryScreen.Bounds.Width
    Dim theHeight As Integer = DeskTop.PrimaryScreen.Bounds.Height
    MsgBox(theWidth & "x" & theHeight)
  End Sub
```

