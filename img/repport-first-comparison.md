# Cholesky Hedgehog

## Computation times depending on threads repartition and block size for a 40000x40000 matrix

| threads / block sizes_list | 1024 |
|---|---|
| 1-12-176 | 6926.3ms +- 163.817ms |
| 1-12-168 | 7061.65ms +- 137.161ms |
| 1-12-240 | 6770.55ms +- 141.733ms |
| 1-12-200 | 6880.2ms +- 164.985ms |
| 1-12-88 | 8583.0ms +- 752.937ms |
| 1-12-104 | 8097.4ms +- 922.497ms |
| 1-12-216 | 6778.55ms +- 106.323ms |
| 1-12-256 | 6799.65ms +- 117.906ms |
| 1-12-144 | 7324.75ms +- 332.031ms |
| 1-12-72 | 9466.5ms +- 847.505ms |
| 1-12-32 | 13628.25ms +- 95.165ms |
| 1-12-64 | 9732.1ms +- 260.098ms |
| 1-12-56 | 10031.95ms +- 368.598ms |
| 1-12-120 | 7733.45ms +- 490.440ms |
| 1-12-24 | 17080.7ms +- 71.319ms |
| 1-12-192 | 6854.15ms +- 139.610ms |
| 1-12-112 | 8080.7ms +- 933.793ms |
| 1-12-96 | 8964.75ms +- 558.731ms |
| 1-12-136 | 7463.85ms +- 412.511ms |
| 1-12-152 | 7178.9ms +- 111.568ms |
| 1-12-80 | 9046.3ms +- 640.818ms |
| 1-12-224 | 6766.2ms +- 146.692ms |
| 1-12-8 | 49038.4ms +- 81.191ms |
| 1-12-40 | 11880.65ms +- 169.040ms |
| 1-12-208 | 6781.5ms +- 123.796ms |
| 1-12-232 | 6725.55ms +- 144.220ms |
| 1-12-248 | 6792.75ms +- 118.216ms |
| 1-12-184 | 6911.85ms +- 138.028ms |
| 1-12-48 | 10919.0ms +- 78.150ms |
| 1-12-128 | 7561.9ms +- 395.504ms |
| 1-12-16 | 24898.05ms +- 121.978ms |
| 1-12-160 | 7078.9ms +- 165.988ms |

Best HH: threads = 1, 12, 232, block_size 1024: 6725.55
Best Lapack: threads = 96: 9279.4
Speedup max: 1.3797235913791437

