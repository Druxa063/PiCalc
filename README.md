# PiCalc

# How to execute

Before start the app please follow this [guide](https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html)

---
Note: you need to have compatible GPU, [list](https://developer.nvidia.com/cuda-gpus) of allowed GPUs
---

# Results

The results were tested on GeForce 840M.

| Length of random vectors   | CPU, ms       | CPU, result | GPU, ms  | CPU, result |  
| -------------              |:-------------:| -----:      | -----:   | -----:      |
| 1048576                    | 0.011000      | 3.141502    | 0.002074 | 3.141502    |  
| 16777216                   | 0.170000      | 3.141953    | 0.023577 | 3.14953     |
| 33554432                   | 0.367000      | 3.141278    | 0.042616 | 3.141278    |
