## Real Time Applications



1. Harry potter's Invisibility cloak was passed down to him by his father James and James potter got it from his father Henry potter, this is a clear example for?

   ![EASY](https://github.com/revaturelabs/JavaFSQuestions/blob/main/Java/JavaIntro/JavaFeatures/Easy%20(2).jpg)

- A.Hybrid Inheritance
- B.Multilevel Inheritance
- C.Simple Inheritance
- D.Multiple Inheritance

<details><summary> <b>Hint </b></summary>
  
  Invisibility Cloak is an object and harry,james and herny are classes.
  </details>

<details><summary> <b>Show Answer</b> </summary>
  
  **Ans**: B
  
  **Explanation**: Invisibility Cloak is a family heirloom for potters, A property is passed down from one class(generation) to another, this is a clear example of multilevel inheritance
</details>




## Technical

1. Is it possible to overload the main method? if yes, which of the main method is considered as the main thread and implemented first?

    ![HARD](hard.jpg)



<details><summary> <b>Show Answer</b> </summary>
  
  **Ans**: Yes
  
  **Explanation**: the main method like any other method can be overloaded, in such a scenario, java launcher will search for "public static void main(String[] args)" and implementes it first.
  
</details>

## Probelm solving

1. Predict the output.

    ![HARD](hard.jpg)
``` java
  class Selection {
        public static void main(String args[]){
            int var1 = 5; 
            int var2 = 6;
            if ((var2 = 1) == var1)
                System.out.print(var2);
            else 
                System.out.print(++var2);
        }
        
   ```
 


<details><summary> <b>Show Answer</b> </summary>
  
  **Ans**: 2
  
  **Explanation**:  In the "if" condition the value for var2 is changed to 1,Since var1 is not equal to var2, the else condition is implemented, in the else condition var2 is incremented by one, so the output is 2. 
  </details>
  


## Error Detection / Debugging

1. Predict the output of the program and debug the program.  

    ![Medium](https://github.com/revaturelabs/JavaFSQuestions/blob/main/Java/JavaIntro/JavaFeatures/Project%203%20(2).jpg)       

``` java
public class Numbers{ 

     public static void main(String[] args)  {
            numbers(); 
     } 
     static int printNumbers() { 
          while(true) { 
              System.out.println("Universe is Infinite"); 
          } 
          System.out.println(Integer.MAX_VALUE); 
     } 
} 
```
  
  - A.Compile time error
  - B.Runtime error
  - C.Universe is Infinite
  - D.2147483647
  
  
  <details>
  <summary> <b>Show Answer</b> </summary>
  
  **Ans**: A
  
  **Explanation**: the outcome of the program is the compile-time error and it's caused by the unreachable statement after the infinite while loop.
  
  </details>
  








