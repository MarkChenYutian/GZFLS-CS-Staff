# AP Computer Science A Paper

## Multiple Choise (13 Questions, Suggest Time: 30 Min)
1. Consider the following code segment
   ```java
   int n = 10;
   while (n < 20){
       System.out.println(n);
       n ++;
   }
   ```
   What are the first and last numbers output by the program?
   
   a. 10, 20

   b. 10, 19

   c. 11, 20

   d. 11, 19

2. Consider the following code segment
   ```java
    int x = 7;
    int y = 3;
    if ( (x<10) && (y<=0) ){
        System.out. println(x * y);
    }
    else{
        System.out.println(x/y);
    }
   ```
   What is the output of code segment?

   a. 2

   b. 21

   c. 2.33333333333

   d. 2.0

3. `!(!( a!=b || a < 5)) && (b > 7))` is equivalent to which of the following?
   a. `a != b || a < 5 || b > 7`
   
   b. `a == b && a >= 5 || b <= 7`
   
   c. `a == b || a >= 5 && b > 7)`
   
   d. `a != b && a < 5 || b <= 7)`
  
4. Consider the following code segment ...
   ```java
   public static String coding(String input){
      String output = "";
      while input.length() > 1{
         output += input.substring(input.length()-2,input.length());
         input = input.substring(0,input.length()-2);
      }
      Syetem.out.println(output);
   }
   ```
   What is the output of `coding("Happy_AP_CS_A!");`
   
   a. "Happy_AP_CS_A!"
   
   b. "A!S__CAPy_ppHa"
   
   c. "!A_SC_PA_yppaH"
   
   d. "A!_CS_AP_Happy"
  
5. Which line of code should be written to transfer `ArrayList<int> test` from `[1, 3, 5, 2]` to `[1, 2, 4, 5, 2]`?
   
   a. 
      ```java
      test.insert(1, 2);
      test.set(2, 4);
      ```
   
   b. 
      ```java
      test.insert(2, 1);
      test.set(4, 2);
      ```
   
   c. 
      ```java
      test.insert(1, 0);
      test.set(
      ```
   
   d.
    
## Free Response Questions (3 Questions, Suggest Time: 30 Min)
