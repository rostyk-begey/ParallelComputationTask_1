# Parallel Computation - Matrix Mathematical Operations

## Input data

matrix N * N  
add: N = 1000  
multiply: N = 100  

## Successive results

add: T = ~76s  
multiply: T = ~24.42s

## Multithread results

* ### 2 threads

  add: T = ~85s; S = 0.89; E = 0.445  
  multiply: T = ~26.36s; S = 0.92; E = 0.46

* ### 4 threads

  add: T = ~101s; S = 0.75; E = 0.1875  
  multiply: T = ~34.66s; S = 0.7; E = 0.175

* ### 8 threads

  add: T = ~127s; S = 0.59; E = 0.07375  
  multiply: T = ~41.97s; S = 0.58; E = 0.0725

* ### 16 threads

  add: T = ~171s; S = 0.44; E = 0.0275  
  multiply: T = ~36.4s; S = 0.67; E = 0.041875
