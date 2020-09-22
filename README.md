<div align="center">

## Simple Interest Calculator \( update 1\) \- Now used to find Amount also \!


</div>

### Description

Make this program and you have a total Interest calculator ...

If anyone knows how to fix the bugs ,please mail me with the code and I will update it .
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[ComputerWhiz](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/computerwhiz.md)
**Level**          |Beginner
**User Rating**    |4.0 (32 globes from 8 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/computerwhiz-simple-interest-calculator-update-1-now-used-to-find-amount-also__1-40763/archive/master.zip)





### Source Code

```
Make three textboxes with the names :- txtPrinciple, txtRI, txtTime Respectively . Then make a command button and name it cmdAnswer . Then make a variable - AnswerGot
i.e dim AnswerGot
After that ,make a label control and name it lblAnswer
Now ,in the click event of the cmdAnswer add this code :-
lblAnswer.Caption = AnswerGot
AnswerGot = txtprinciple * txtRI * txtTime / 100
Now ,for the updated part ,to get the amount -
Make a label and name it lblAmount
Make a command button and name it cmdAmount
Make a variable - AmountAns
In the click event of cmdAmount add -
lblAmount.caption = AmountAns
AmountAns = txtPrinciple + lblAnswer
_________________________________________________ ***** Please vote for this article .I will very highly appreciate your voting ....
```

