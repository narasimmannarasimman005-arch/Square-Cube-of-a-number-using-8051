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
ORG 00H

MOV R0,#50H

MOV A,@R0

MOV B,A

MUL AB

INC R0

MOV @R0,A

END

##Calculation

<img width="1556" height="1146" alt="image" src="https://github.com/user-attachments/assets/6e1e2485-7abf-4986-9b4f-4e7a32b71d71" />








```

## OUTPUT
<img width="984" height="592" alt="image" src="https://github.com/user-attachments/assets/ca9e822e-1da5-4659-a88f-4982a6a70c6f" />



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
ORG 00H

MOV R0,#50H

MOV A,@R0

MOV B,A

MUL AB

MOV B,@R0

MUL AB

INC R0

MOV @R0,A

INC R0

MOV @R0,A

END


##Calculation
<img width="1568" height="1234" alt="image" src="https://github.com/user-attachments/assets/bdb42c68-527d-49e1-a45c-b799737704fb" />






```


## OUTPUT
<img width="993" height="719" alt="image" src="https://github.com/user-attachments/assets/017e501a-7f13-44e7-8431-d7148a983784" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


