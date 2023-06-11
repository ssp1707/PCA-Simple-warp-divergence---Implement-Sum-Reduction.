# Simple warp divergence-Implement Sum Reduction.

## Aim:
The aim of this experiment is to compare the performance of two CUDA kernels, reduceUnrolling8 and reduceUnrolling16, which handle 8 and 16 data blocks per thread, respectively.

## Procedure:
The experiment follows the following steps:

1. Initialize an input array of size 1024.
2. Launch the reduceUnrolling8 kernel, which performs reduction using 8 data blocks per thread.
3. Launch the reduceUnrolling16 kernel, which performs reduction using 16 data blocks per thread.
4. Compare the results obtained from both kernels.

## Output:
The program outputs the results of the reduction performed by each kernel. Specifically, it displays the final reduced value obtained from the reduceUnrolling8 kernel and the reduceUnrolling16 kernel.
![image](https://github.com/Kavya-Bollineni22/PCA-Simple-warp-divergence---Implement-Sum-Reduction./assets/75235813/22b31b14-1a5f-48b0-b620-a02caa8184f3)
![image](https://github.com/Kavya-Bollineni22/PCA-Simple-warp-divergence---Implement-Sum-Reduction./assets/75235813/9186b1ed-5fff-435a-a11f-13dc2114e1da)

## Result:
The performance of the two kernels can be compared based on the reduction results. A higher reduction result indicates a more efficient reduction algorithm. The comparison between the two results can provide insights into the performance difference between the kernels.
