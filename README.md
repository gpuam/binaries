# binaries
Binary file for GPUs

If you use this code please cite :
* Raymundo Hernández-Esparza, Álvaro Vázquez-Mayagoitia, Luis A. Soriano-Agueda, Rubicelia Vargas, and Jorge Garza. GPUs as boosters to analyze scalar and vector fields in quantum chemistry. Int. J. Quantum Chem. 119, e25671 (2019). DOI: 10.1002/qua.25671
* Raymundo Hernández-Esparza, Sol-Milena Mejía-Chica, Andy D. Zapata-Escobar, Alfredo Guevara-García, Apolinar Martínez-Melchor, Julio-M. Hernández-Pérez, Rubicelia Vargas, and Jorge Garza. Grid-Based Algorithm to Search Critical Points, in the Electron Density, Accelerated by Graphics Processing Units. J. Comput. Chem. 35, 2272-2278 (2014). DOI: 10.1002/jcc.23752

At this moment we provide binary files optimized for Intel compilers. If you are interested in the source code, please ask to Jorge Garza (jgo@xanum.uam.mx).

libiomp5.so (just in case). If you do not have Intel compilers then put this file in the directory of your preference and execute

export LD_LIBRARY_PATH=name_directory_of_libiomp5.so:$LD_LIBRARY_PATH 

Running GPUAM

GPUAM will search within the working directory WFN, WFX or MGF files. Use the following commands to execute this program.

./Gpuam_GPU.x

or

./Gpuam_GPU.x < input_file 

See GPUAM_manual.pdf file and two examples provided in test directory
