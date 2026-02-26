==================================================
SYSTEM INFORMATION
==================================================
OS:         Darwin 24.1.0
Version:    Darwin Kernel Version 24.1.0: Thu Oct 10 21:05:14 PDT 2024; 
Machine:    arm64
Processor:  arm
Python:     3.11.6 (v3.11.6:8b6ee5ba3b, Oct  2 2023, 11:18:21) [Clang 13.0.0 (clang-1300.0.29.30)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0445 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0277 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0097 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0445s
  list benchmark:   0.0277s
  string benchmark: 0.0097s
  Total RAM: 8 GB
