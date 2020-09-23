<div align="center">

## \[ Crazy Form \]


</div>

### Description

This code makes the form jump around the screen and changes it's size. Please vote and comment :)
 
### More Info
 
One Timer called, Timer1, with an interval of about 100.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[JamesJD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jamesjd.md)
**Level**          |Beginner
**User Rating**    |3.9 (77 globes from 20 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Jokes/ Humor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/jokes-humor__1-40.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jamesjd-crazy-form__1-48472/archive/master.zip)





### Source Code

```
Private Sub Timer1_Timer()
  Dim Height As String
  Dim Width As String
  Dim Top As String
  Dim Left As String
  Randomize
  Height = Int(Rnd * 10000)
  Width = Int(Rnd * 10000)
  Top = Int(Rnd * Screen.Height)
  Left = Int(Rnd * Screen.Width)
  Form1.Height = Height
  Form1.Width = Width
  Form1.Top = Top
  Form1.Left = Left
End Sub
```

