# cupti_test

./metrics.sh

```
Usage: build/autorange [device_num] [metric_names comma separated]
CUDA Device Number: 0
Compute Capability of Device: 8.6
CUPTI_KernelReplay
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
rangeName: 0    metricName: smsp__cycles_elapsed.avg    gpuValue: 1.76025e+06
rangeName: 0    metricName: smsp__cycles_elapsed.avg.per_second gpuValue: 1.39511e+09
rangeName: 0    metricName: sm__throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 15.4978
rangeName: 0    metricName: gpu__compute_memory_throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 93.3491
rangeName: 0    metricName: dram__bytes_read.sum        gpuValue: 7.159e+08
rangeName: 0    metricName: dram__bytes_write.sum       gpuValue: 3.57661e+08
rangeName: 1    metricName: smsp__cycles_elapsed.avg    gpuValue: 1.75964e+06
rangeName: 1    metricName: smsp__cycles_elapsed.avg.per_second gpuValue: 1.33174e+09
rangeName: 1    metricName: sm__throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 15.5032
rangeName: 1    metricName: gpu__compute_memory_throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 93.3772
rangeName: 1    metricName: dram__bytes_read.sum        gpuValue: 7.15831e+08
rangeName: 1    metricName: dram__bytes_write.sum       gpuValue: 3.57679e+08

Compute Capability of Device: 8.6
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
Launching kernel: blocks 349526, thread/block 256
rangeName: 0    metricName: smsp__cycles_elapsed.avg    gpuValue: 1.76233e+06
rangeName: 0    metricName: smsp__cycles_elapsed.avg.per_second gpuValue: 1.39896e+09
rangeName: 0    metricName: sm__throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 15.4795
rangeName: 0    metricName: gpu__compute_memory_throughput.avg.pct_of_peak_sustained_elapsed    gpuValue: 93.2412
rangeName: 0    metricName: dram__bytes_read.sum        gpuValue: 7.15839e+08
rangeName: 0    metricName: dram__bytes_write.sum       gpuValue: 3.57742e+08
```
