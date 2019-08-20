
Ceres Solver for Android Platform
=================================

This project is modified based on Ceres V2.0.0`master branch`(https://github.com/ceres-solver/ceres-solver)  
But original version is not supported for all solver methods and you may only use `DENSE_QR`.  
If you want to use some methods(ex.`SPARSE_SCHUR`) and you will find you can't use them.
So, I modified and make sure it is supported for `suites-parse` and you can use it for all solvers(ex.trust_region_strategy or `SPARSE_NORMAL_CHOLESKY` and so on)!  

## What I change
For supported for `suite-sparse`  
Firstly, I add suitesparse libraries(.so) under `3rdParty`  
Secondly, I modified both CMakeLists.txt under `root path` and `internal/ceres` to force compile SuiteSparse module and add suitesparse libraries depended.  

## Prepare for
You should download NDK(Mine is android r16) and add NDK path to your environment variable.  

## How to Compile
Follow command below, and you will get libceres.so for Android platform in `android_build/lib/`  
`cd android_build`  
`sh make_ceres.sh` (you should change ndk path according to your own)  
`make`  
and libceres.so will be saved  
