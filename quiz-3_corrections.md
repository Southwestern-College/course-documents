# Quiz 3 Corrections
1. Find the output generated by the following while loop.
    ```
    int b = 5;
    while (b < 20){
        System.out.println("b = " + b);
        b = b + 7;
    }
    ```
    **Answer**:
    ```
    b = 5
    b = 12
    b = 19
    ```
    **Correction**: _WRITE CORRECTIONS HERE!_
   
    
2. Complete the trace table for each variable in the following code segment.
    ```
    int i = 1, j = 2, count = 1;
        while (count < 3){
            i = i + j;
            j = i - j;
        count++;
    }
    ```
    **Answer**:

   | `i` | `j` | `count` |
   |-----|-----|---------|
   | 1   | 2   | 1       |
   | 3   | 1   | 2       |
   | 4   | 3   | 3       |

    **Correction**: _WRITE CORRECTIONS HERE!_
   

3. How many iterations are carried out by the following loop?
    ```
    int a = 25;
    while (a <= 35){
        System.out.println(" a = " + a);
        a++;
    }
    System.out.println(" a = " + a);
    ```
    **Answer**:
    11 iterations

    **Correction**: _WRITE CORRECTIONS HERE!_
   

4. How many iterations are carried out by the following loop?
   ```
   int a = 4;
   while (a <= 10 && a % 4 == 0){
       System.out.println(" a = " + a);
       a = a + 2;
   }
   System.out.println(" a = " + a);
   ```
   **Answer**:
   1 iteration

   **Correction**: _WRITE CORRECTIONS HERE!_
   

5. Create a trace table for each variable in the following code segment.
   ```
   int i = 1;
   do {
       if (i <= 4) {
           i = 4 * i;
       } else {
           i = i + 5;
       }
   } while (i < 20);
   ```
   **Answer**:

   | `i` |
   |-----|
   | 1   |
   | 4   |
   | 16  |
   | 21  |
    
   **Correction**: _WRITE CORRECTIONS HERE!_
   

6. Write a _while_ loop that displays all multiples of 4 from 8 to 48, inclusive.

   **Answer**:
   ```
   int i = 8;
   while (i <= 48) {
      System.out.println(i);
      i += 4;
   }
   ```
   **Correction**: _WRITE CORRECTIONS HERE!_
   

7. Write a while loop that finds the sum of the first ten perfect-squares, i.e. find the sum $1^2 + 2^2 + 3^2 + ... + 9^2 + 10^2$.
   **Answer**:
   ```
   int i = 1;
   int sum = 0;
   while (i <= 10) {
      sum += i * i;
      i++;
   }
   ```
   **Correction**: _WRITE CORRECTIONS HERE!_
   

9. Create a trace table for the variable in
   ```
   for (int i = 0; i < 7; i++){
       if (i%2 == 0){
           i = i + 2;
       } else {
           i = i * 2;
       }
   }
   ```
   
   **Answer**:
   
   | `i` |
   |-----|
   | 0   |
   | 2   |
   | 3   |
   | 6   |
   | 7   |
   
   **Correction**: _WRITE CORRECTIONS HERE!_
   

10. How many iterations are carried out by the following loop?
   
      ```
      for (int j = 9; j < 50; j = j + 7) {
          if (j % 3 == 0) {
              System.out.println("j = " + j);
          }
      }
      ```
      
      **Answer**:
      6 iterations
      
      **Correction**: _WRITE CORRECTIONS HERE!_
      

11. How many iterations are carried out by the following loop?
      ```
      for (int j = 1, k = 1; j < 5 || k % 3 == 0; j = j + 2, k++){
          if (j % k == 0) {
              System.out.println(j % k);
          }
      }
      ```
      **Answer**:
      3 iterations
      
      **Correction**: _WRITE CORRECTIONS HERE!_
      

12. Write a for loop that prints out the string str in reverse. For example, "bat" would be displayed as tab. Assume str has been declared and initialized.

      **Answer**:
      ```
      String reverse = "";
      for (int i = 0; i  < str.length(); i++) {
          reverse = str.charAt(i) + reverse;
      }
      System.out.print(reverse);
      ```
      **Correction**: _WRITE CORRECTIONS HERE!_
      

14. Write a nested for loop that displays the pattern.
      ```
      X
      O X
      O O X
      O O O X
      ```
      **Answer**:
      ```
      for (int i = 1; i <= 4; i++) {
      for (int j = 1; j <= i; j++) {
      if(i == j) {
      System.out.print("X");
      } else {
      System.out.print("O");
      }
      }
      System.out.println();
      }    
      ```

      **Correction**: _WRITE CORRECTIONS HERE!_
