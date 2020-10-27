---
title: time_taken
tags: utility, beginner
---

Calculates time taken by a function.
- Pass function name as argument.
- The `time_taken` function calls the function.
- It then returns the time taken to run the function.

```py
import time

def time_taken(function_name):
  start_time = time.time()
  function_name()
  end_time = time.time()
  total_time = end_time - start_time
  return total_time
```

```py
time_taken(function_name)
```
