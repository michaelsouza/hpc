hello_mpi:hello_mpi.c
	mpicc hello_mpi.c -o hello_mpi 
	
run_hello_mpi:hello_mpi
	mpirun -n 4 ./hello_mpi.exe
	
hello_omp:hello_omp.c
	gcc hello_omp.c -fopenmp  -o hello_omp