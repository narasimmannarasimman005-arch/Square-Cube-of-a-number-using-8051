# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```

<img width="430" height="530" alt="image" src="https://github.com/user-attachments/assets/b06a35ca-2429-46de-b9e5-8b5168bce012" />








```

## OUTPUT


<img width="315" height="197" alt="image" src="https://github.com/user-attachments/assets/0a496301-cf2d-4baa-91dd-296dfb4fd94b" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```

ORG 0000H
LJMP MAIN

ORG 0030H
MAIN:
    MOV R0, #05H
    
    MOV A, R0
    MOV B, R0
    MUL AB
    MOV R1, A
    MOV R2, B
    
    MOV A, R1
    MOV B, R0
    MUL AB
    MOV R3, A
    MOV R4, B
    
    MOV A, R2
    MOV B, R0
    MUL AB
    
    ADD A, R4
    MOV R5, A
    
    MOV A, B
    ADDC A, #00H
    MOV R6, A

HERE: SJMP HERE
END







```


## OUTPUT

<img width="327" height="246" alt="image" src="https://github.com/user-attachments/assets/0e699e58-5583-43c8-851d-ee617d106b3c" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


