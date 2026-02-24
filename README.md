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

ORG 0000H
MOV R0, #30H     
MOV A, @R0      
MOV R1, A         
MOV A, #01H     
FACT:
MOV B, R1        
MUL AB           
DJNZ R1, FACT    
MOV 31H, A       
END


```

## OUTPUT

<img width="890" height="514" alt="image" src="https://github.com/user-attachments/assets/8bd2358c-1ca6-4c18-8ce5-2f8fd28501d1" />
<img width="869" height="601" alt="image" src="https://github.com/user-attachments/assets/7e021373-e947-4771-b48d-eb1497eedc18" />

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
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END




```


## OUTPUT
<img width="929" height="651" alt="image" src="https://github.com/user-attachments/assets/4e7a572f-6aa4-4eb9-ad57-26e8dd95117f" />
<img width="843" height="617" alt="image" src="https://github.com/user-attachments/assets/0d2676a0-c903-41c5-b146-2a45714fd622" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


