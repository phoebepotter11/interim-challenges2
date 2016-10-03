# interim-challenges2

# Interim Challenges

### Today I wrote code.

### The easiest part was inputting the scanners and strings.

### The most difficult part was figuring out how to input the if statements.

### I would describe my confidence with Java as: Okay

### The A level I would like at the end of Summer 2018 is A

```java
package interim.challenge.pkg4;

import java.util.Scanner;

public class INTERIMCHALLENGE4 {

    
    public static void main(String[] args) {
         Scanner myScanner = new Scanner (System.in);
        // this inputs the scanner. It scans whatever you ask it to.
        System.out.println("Please enter your age");
        // this tells the person what to do
        int age = myScanner.nextInt();
        // this is where the scanner is used. It is being told to scan the next line (what the person has written next).
        if (age>17) {
            System.out.println("You are able to vote.");
        }
        // this allows the programme to say a certain thing based on what the person has input. If the person inputs their age as 18 or above then they will be told they are able to vote.
        if (age<18) {
            System.out.println("You aren't able to vote.");
        }
        //If the person inputs their age as lower than 18, then they will be told they aren't allowed to vote.
        
        if (age>16) {
            System.out.println("You are able to drive");
        }
        
        if (age<17) {
            System.out.println("You are not able to drive.");
        }
        
      
    }
    
}
```
