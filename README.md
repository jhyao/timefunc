# functime
## install
```
pip install functime
```
## usage
```python
import functime

func_time(sorted, [5,4,3,2,1])
```
out:
```
sorted AVG(1000000): 0.537999us
```
This moudle provides a simple way to time a function.
* timer_auto(func, *args, **kwargs):
  Recommended function.Time func with its arguments followed by func.Call timer(func, times) repeatedly with times set to (10, 100, 1000, ...) so that the total time >= 0.2.Print average run time with readable format.