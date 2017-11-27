# Comparison-between-serial-and-parallel-implementation-of-Machine-Learning-algorithm-K-Means-.-

# parallelmachinelearning


Parallel implementation of machine learning algorithms using OpenMP

=========Serial Implementation=======


Running the serial.c in DOZER


1. Copy the "color.txt" file in the local profile of DOZER


2. compile the seq.c program


   gcc seq.c -o seq


3. Running the seq file


   ./seq color.txt
   
   
   Then you will be promoted with the number of cluster, enter the number of cluster.


///////////OUTPUT/////////////


4. The time will be returned


5. Two files will be created which consists of images membership and the final cluster centroid location 


=======Parallel Implementation==========


Running the parallel.c in DOZER


1. Copy the "color.txt" file in the local profile of DOZER


2. compile the seq.c program


   gcc -O -fopenmp para.c -o para


3. Running the seq file


   ./para color.txt
  
  
  Then you will be promoted with the number of cluster, enter the number of cluster.


///////////OUTPUT/////////////


4. The time will be returned


5. Two files will be created which consists of images membership and the final cluster centroid location 

