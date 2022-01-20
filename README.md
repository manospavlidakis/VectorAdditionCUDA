# VectorAdditionCUDA
A simple example for Vector Addition using CUDA

# Compile
nvcc vectorAddition.cu -o vectorAddition

# Run
./vectorAddition

# Download and Install CUDA 
Follow the instructions in https://developer.nvidia.com/cuda-downloads

# Add to your bashrc the following
export CUDA_HOME="/usr/local/cuda"
export LD_LIBRARY_PATH=${CUDA_HOME}/lib64:$LD_LIBRARY_PATH
export PATH=${CUDA_HOME}/bin:${PATH}
