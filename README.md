# Втора лабораториска вежба по Софтверско инженерство
## Симона Стризлоска, бр. на индекс 182024
### Група на код:
Ја добив група на код 4
### Control Flow Graph
![Screenshot](ControlFlow.jpg)
### Цикломатска комплексност
Цикломатската комплексност е 9. Според формулата Р+1, Р=(Y,A,D,P,G,J,L,N)=8, 8+1=9.
### Тест случаи според критериумот Every branch
За every branch се тестираат сите јазли.  
Y-A;  
Y-R;  
A-B,C;  
A-R;  
D-E;  
D-R;  
E-F;  
F-G;   
G-P;  
G-J;  
J-K;  
J-L;  
K-L;  
L-M;  
L-N;  
M-N;  
N-O;  
N-H;  
O-H;  
H-G;  
P-R;  
P-Q;  
R-END;  
Q-END; 

### Тест случаи според критериумот Every path
Со every path се тестираат сите патови.   
Y-R-END;  
Y-A-R-END;  
Y-A-B,C-D-R-END;  
Y-A-B,C-D-E-F-G-P-R-END;  
Y-A-B,C-D-E-F-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-L-N-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-L-N-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-K-L-N-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-K-L-N-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-L-M-N-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-L-M-N-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-L-N-O-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-L-N-O-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-K-L-M-N-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-K-L-M-N-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-L-M-N-O-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-L-M-N-O-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-K-L-N-O-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-K-L-N-O-H-G-P-Q-END;  
Y-A-B,C-D-E-F-G-J-K-L-M-N-O-H-G-P-R-END;  
Y-A-B,C-D-E-F-G-J-K-L-M-N-O-H-G-P-Q-END;  
### Објаснување на напишаните unit tests
