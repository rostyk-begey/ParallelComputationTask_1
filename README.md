# Parallel Computation - Matrix Mathematical Operations

## Input data

matrix N * N  
add: N = 10000  
multiply: N = 1000  

## Successive results

add: T = ~76s  
multiply: T = ~24.42s

## Multithread results

### Add

threads: 2  
time: 4.77061s  
S = 0.956107  
E = 0.478054  

threads: 4  
time: 4.82403s  
S = 0.945518  
E = 0.23638  

threads: 8  
time: 6.39117s  
S = 0.713673  
E = 0.0892092  

threads: 16  
time: 6.31402s  
S = 0.722394  
E = 0.0451496  

### Multiply

threads: 2  
time: 9.1787s  
S = 1.01878  
E = 0.509388

threads: 4  
time: 9.83328s  
S = 0.950958  
E = 0.237739

threads: 8  
time: 17.3434s  
S = 0.539171  
E = 0.0673963

threads: 16  
time: 17.5489s  
S = 0.532855  
E = 0.0333034
