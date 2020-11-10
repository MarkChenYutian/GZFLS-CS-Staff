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

9. Consider the following function

   ```java
   public static int findValueIndex(int[] arr, int n){
       //missing section   
   }
   ```

   Placing which segment of code in position "missing section" will make the function be able to help us find the index of specific value in array (if there does not exist such a value, return -1)?

   a. 

   ```java
   for (int i = 0; i < arr.length; i++){
       if (arr.get(i) == n){
           return n;
       }
       else{
           return -1;
       }
   }
   ```

   b.

   ```java
   for (int i = 0; i < arr.length; i++){
       if (arr[i] == n){
           return n;
       }
       return -1;
   }
   ```

   c.

   ```java
   for (int i = 0; i < arr.size(); i++){
       if (arr[i] == n){
           return i;
       }
   }
   return -1;
   ```

   d.

   ```java
   for (int i = 0; i < arr.length; i++){
       if (arr[i] == n){
           return i;
       }
   }
   return -1;
   ```

10. Consider the following code segment that aims to find the mean value of a given `ArrayList` of integers.

    ```java
    public static double Function(ArrayList<int> arr){
        int s = 0;
        for (int i = 0; i < arr.size(); i ++){
            s += arr.get(i);
        }
        return s / arr.size();
    }
    ```

    Will this code work accurately?

    a. Yes

    b. No, since we should use `arr.length` to get the length of `arr` instead of `arr.size()` 

    c. No, since we should use `s // arr.size()` instead of `s / arr.size()` on the last line.

    d. No, since dividing two integers `s` and `arr.size()` will make the result inaccurate.

13. Consider the following method.
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

## Free Response Questions (3 Questions, 30 Min)

