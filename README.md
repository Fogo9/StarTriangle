# **STAR TRIANGLE**

## INFORMATION

* **In this program, the crystal shape is displayed with the star symbol.**

## TECHNOLOGIES USED

* **JAVA**

## CONTENTS

* The variables **n**, **i**, **k** and **j** are defined with int.

* Scanner class created for user to enter numbers.

* Formulas were used to get the crystalline shape in the for loop.

## CODES

```Java

        import java.util.Scanner;

        public class startriangle{

            public static void main(String[] args) {

                int n;

                Scanner input = new Scanner(System.in);

                System.out.print("Enter The Number : ");

                n = input.nextInt();


```

```Java

                for(int i = 0; i <= n; i++){

                    for(int k = 0; k < (n - i); k++){

                        System.out.print(" ");

                    }

                    for(int j = 0; j < (2*i) - 1; j++){

                        System.out.print("*");

                    }
                    System.out.println();

                }
                for(int i = n - 1; i >= 0; i--){

                    for(int k = 0; k < (n - i); k++){

                        System.out.print(" ");

                    }

                    for(int j = 0; j < (2*i) - 1; j++){

                        System.out.print("*");

                    }
                    System.out.println();

                }
            }
        }

```

```bash

Enter The Number : 10

         *
        ***
       *****
      *******
     *********
    ***********
   *************
  ***************
 *****************
*******************
 *****************
  ***************
   *************
    ***********
     *********
      *******
       *****
        ***
         *

```

<br />

## LINK

* Click here https://github.com/Fogo9/StarTriangle.git to access the Github page for this project.

<br />

## LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
