# Speed Test methods

### single-pass 
| Test | Method   | Time      | Memory    |
|------|----------|-----------|-----------|
| 1    | map      | ~ 1.00 ms | 1.6 - 4.0 |
| 2    | for      | ~ 0.65 ms | 1.6 - 4.0 |
| 3    | forOf    | ~ 1.53 ms | 1.6 - 4.0 |
| 4    | reduce   | ~ 2021 ms | 1.6 - 4.0 |
| 5    | while    | ~ 0.73 ms | 1.6 - 4.0 |

### multidecade-pass 1k
| Test | Method   | Time      | Memory    |
|------|----------|-----------|-----------|
| 1    | map      | ~ 422 ms  | 1.6 - 4.1 |
| 2    | for      | ~ 81 ms   | 1.6 - 8.7 |
| 3    | forOf    | ~ 715 ms  | 1.6 - 3.8 |
| 4    | reduce   | ~ error   | --------  |
| 5    | while    | ~ 82.4 ms | 1.6 - 8.7 |

### multidecade-pass(100)
| Test | Method   | Time     | Memory     |
|------|----------|----------|------------|
| 4    | reduce   | ~ 9.1 ms | 1.6 - 16.0 |
