# WriteBinaryFile
Some simple tools to generate binary files easily


## generate matrix for WarpAffine

### Usage: 

compile generate_warAffine_matrix.cpp

then ./a.out a00 a01 a02 a10 a11 a12 output_file.bin

```
g++ generate_warAffine_matrix.cpp -o generate_warAffine_matrix
./generate_warAffine_matrix 1 0 -0.5 0 -1 0.5 matrix.bin
```


### Note

TODO: wrtie a makefile

key phrases: C++, ofstream, write bin file, float array to bin, argc, argv, atof
