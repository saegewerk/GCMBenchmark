#GCMBenchmark
## Build
### Windows
```
.\build.bat
```
### Linux
```
.\build.sh
```
## Run
```
cd build
```
### Windows
```
.\GCMBenchmark.exe
```
### Linux
```
.\GCMBenchmark
```
Example output
```
Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz - 8 Logical Cores  - 4 Cores
+----------+--------+-------------+
| ROUTINES |    OPS | TIME PER OP |
+----------+--------+-------------+
|        8 |  10000 |     8.975µs |
|        8 | 100000 |     7.848µs |
|        8 | 500000 |      7.55µs |
|        4 |  10000 |    10.571µs |
|        4 | 100000 |    10.623µs |
|        4 | 500000 |    10.806µs |
|        2 |  10000 |    13.164µs |
|        2 | 100000 |    13.131µs |
|        2 | 500000 |    13.407µs |
|        1 |  10000 |    21.143µs |
|        1 | 100000 |    21.458µs |
|        1 | 500000 |    21.738µs |
+----------+--------+-------------+
```