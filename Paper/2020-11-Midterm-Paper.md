# AP Computer Science A Paper

## Multiple Choice (13 Questions, Suggest Time: 30 Min)
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
      test.set(1, 4);
      ```
   
   d.
      ```java
      test.insert(0, 2);
      test.set(1, 4);
      ```   
   
6. Consider the following function

   ```java
   public static void Function(int n){
       double i = 2;
       int m = 3;
       System.out.println(i + n / m);
   }
   ```

   What will be the output of `Function(2)`

   a. 2

   b. 2.0

   c. 1

   d. 1.0

7. Consider the following function

   ```java
   public static int MysteryFunc(int p, int q)
       int n = 0;
       for (int i = 0; i < p; i ++){
           for (int j = 0; j < q; j ++){
               n++;
           }
       }
       return n;
   ```

   Which of the formula below has same effect?

   a. `n = p + q;`

   b. `n = p * q;`

   c. `n = pq + pq + ... + pq;` (with `p` `pq` terms)

   d. `n = Math.pow(p, q);`

8. Observe the following code segment

   ```java
   public static void main(String[] args) {
       int[] a = new int[3];
       int[] b = {1, 2, 3};
       a = b;
       b[1] = 7;
       System.out.println(a[1]);
       System.out.println(b[1]);
   }
   ```

   What will be the output of this function?

   a. 

   ```
   1
   1
   ```

   b.

   ```
   2
   2
   ```

   c. 

   ```
   2
   7
   ```

   d.

   ```
   7
   7
   ```

9. Consider the following code segment.

   ```java
   int[] arr = {2, 8, 6, 4, 10, 31, 15, 18, 11};
   int i == 0;
   while (i < arr.length -2 ){
      if (arr[i] < arr[i + 1]){
         System.out.print(arr[i] + " ");
      }
   i++
   }
   ```
      
   What will be printed as a result of executing the code segment?
      
   a. 2 6 10 15
      
   b. 2 4 10 11
      
   c. 2 6 10 11
      
   d. 2 4 10 15 

10. Consider the following method.

    ```java
    public static void main(String args[]) {
      ArrayList<Integer> list = new ArrayList<String>();
      for (int i = 0; i < 10; i++){
          if (list.size() < 4){
            list.add(i);
          }
          else{
            list.remove(0);
          }
      }
      int size = list.size();
      return size;
    }
    ```
    
    What is the result of the method?
    
    a. 2
    
    b. 3
    
    c. 4
    
    d. 5
                             

11. Consider the following code segment.
    
    ```java
    int result = 200;
    for (int i == 0; i < 5; i++){
      if ( /*expression1*/ ) {
         result = result // 10;
      }
      else if ( /* expression2 */ ) {
         retult = result % 2;
      }
      else{
         result = result * 2;
      }
    ```
   
   Which of the following can be used to replace /*expression1*/ and /*expression2*/ so that result is 8
   
   a. /*expression1*/ : result % 10 == 0
         /*expression2*/ : result // 2 > 2

   b. /*expression1*/ : result % 10 ==0
         /*expression2*/ : result // 2 >= 2

   c. /*expression1*/ : result % 5 ==0
         /*expression2*/ : result // 2 >2

   d. /*expression1*/ : result % 5 == 0
         /*expression2*/ : result // 2 >= 2
      
      
12.Consider the following method.

      ```java
      public int Function(int a){
         if (a <= 0){
            return 1;
         }
         else{
            return Function(a - 1) + Function(a - 2);
         }
       }
      ```
      
   What will be the result of `System.out.println(Function(3))`;
   
      a. 2

      b. 3

      c. 4

      d. 5
   
13. Consider the following method.

    ```java
    public int Function(int n){
        int[] ctrlSequence = {3, 5, 11, 25, 36};
        for (int i= ctrlSequence.length - 1; i > 0; i--){
            n = n % ctrlSequence[i];
        }
        return n;
    }
    ```
    
   what is the result of Function(107) ?
   
      a. 2

      b. 10

      c. 0

      d. 3

## Free Response Questions (3 Questions, 30 Min)

