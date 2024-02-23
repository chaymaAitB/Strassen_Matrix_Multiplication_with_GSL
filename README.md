# Strassen_Matrix_Multiplication_with_GSL

This directory contains a C program implementing the Strassen algorithm for matrix multiplication using the GNU Scientific Library (GSL). The Strassen algorithm is a divide-and-conquer method for multiplying matrices, and GSL provides efficient matrix operations required for its implementation.

## Execution

1. **Prerequisites:**
   - Ensure you have a C compiler installed.
   - Install GSL :
     
     [![Build GNU Scientific Library in Linux](https://www.youtube.com/watch?v=dKBLJN4x_7A)](https://www.youtube.com/watch?v=dKBLJN4x_7A)



2. **Clone Repository:**
   ```bash
   git clone [repository_url]
   
3. **Compile and Run:**
   - Open the project in your preferred C IDE (e.g., Visual Studio Code).
   - Compile main program file :
     ```bash
     gcc -Wall -c -I/.../gsl/gsl-install/include main.c
     gcc -Wall -c -I/mnt/c/Users/maron/Downloads/gsl/gsl-install/include main.c // Exemple

   - Link the Compiled Object file with GSL Libraries
     ```bash
     gcc -L/.../gsl/gsl-install/lib main.o -lgsl -lgslcblas -lm
     gcc -L/mnt/c/Users/maron/Downloads/gsl/gsl-install/lib main.o -lgsl -lgslcblas -lm // Exemple
  - Compile in Windows :
     ```bash
     gcc -Wall -c -IC:\\...\\gsl\\gsl-install\\include main.c
     gcc -Wall -c -IC:\\Users\\maron\\Downloads\\gsl\\gsl-install\\include main.c // Exemple

     
     ```bash
     gcc -LC:\\...\\gsl\\gsl-install\\lib main.o -lgsl -lgslcblas -lm
     gcc -LC:\\Users\\maron\\Downloads\\gsl\\gsl-install\\lib main.o -lgsl -lgslcblas -lm // Exemple
     
4. **Result:**
   The program demonstrates the implementation of the Strassen algorithm for matrix multiplication using GSL. It provides an efficient way to multiply matrices of arbitrary size by recursively dividing them into smaller submatrices.
   
  ## Technologies Used
- C programming language
- GNU Scientific Library (GSL)
- IDE: Visual Studio Code
