## Trabalho 3 sobre instruções vetoriais e processamento paralelo com "PTHREAD"

* Compilação:

gcc –std=c11 –pthread –mfma -o matrix_lib_test matrix_lib_test.c matrix_lib.c timer.c

./matrix_lib_test 5.0 8 16 16 8 4 floats_256_2.0f.dat floats_256_5.0f.dat result1.dat result2.dat

ONDE:

5.0 é o valor escalar que multiplicará a primeira matriz <br>
8 é o número de linhas da primeira matriz <br>
16 é o número de colunas da primeira matriz <br>
16 é o número de linhas da segunda matriz <br>
8 é o número de colunas da segunda matriz <br>
4 é o número de threads a serem disparadas <br>
floats_256_2.0f.dat é o nome do arquivo de floats que será usado para carregar a primeira matriz <br>
floats_256_5.0f.dat é o nome do arquivo de floats que será usado para carregar a segunda matriz <br>
result1.dat é o nome do arquivo de floats onde o primeiro resultado será armazenado <br>
result2.dat é o nome do arquivo de floats onde o segundo resultado será armazenado <br>
