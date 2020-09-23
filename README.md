<div align="center">

## simple array


</div>

### Description

Simple code to do a simple thing.....Allows user to enter 10 number and puts those numbers into a number array, the prints it back to the user in reverse.
 
### More Info
 
I wanted to give a little something back to the best source coding site on the web.....this is very simple to do but some beginners might not know how to do it so here it is :)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mike Scarlett](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mike-scarlett.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |Java \(JDK 1\.2\)
**Category**       |[Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/input-output__2-84.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mike-scarlett-simple-array__2-1985/archive/master.zip)





### Source Code

```
import javax.swing.JOptionPane;
public class NumArray
{
 public static void main(String[] args)
 {
  String A;
  int x = 0;
  System.out.println();
  System.out.println("Loading the array with  values going forward");
  System.out.println();
  int[] Num1 = new int[10];
  for (int i = 0; i <=9;i++){
  A = JOptionPane.showInputDialog(null,"Please Enter A Whole Number","Enter A Number",JOptionPane.INFORMATION_MESSAGE);
  x = Integer.parseInt(A);
  System.out.println(x);
  Num1[i]=x;
  x = 0;
 }
 System.out.println();
 System.out.println("Your array going in reverse");
 System.out.println();
  for (int i = 9; i >= 0; i--){
  System.out.println(Num1[i]);
  }
 }
}
```

