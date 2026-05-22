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

 MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END


````
 





 

## OUTPUT
 <img width="713" height="519" alt="image" src="https://github.com/user-attachments/assets/36d32b15-4e75-479b-9d1f-5cf81dd7374c" />
<img width="676" height="495" alt="image" src="https://github.com/user-attachments/assets/b8c8e7c0-0527-4e6a-b3de-1ad491af887b" />




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
 <img width="678" height="514" alt="image" src="https://github.com/user-attachments/assets/34ea3ad7-2f7c-4568-92e6-663f60262f71" />
<img width="536" height="436" alt="image" src="https://github.com/user-attachments/assets/eeaeefb4-4077-492b-929f-9bf170cc5a85" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


