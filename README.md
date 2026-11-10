# rt-detection-bench
 Benchmark of inference servers for real-time object detection on a power-limited laptop GPU. Compares a custom dynamic-batching server against no batching, NVIDIA Triton and Ray Serve by how many 30 FPS camera streams each serves under a 50 ms p99 deadline.
