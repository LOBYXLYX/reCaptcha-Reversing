## Getting CB (CallBack) Parameter
![cb](https://github.com/LOBYXLYX/reCaptcha-Reversing/blob/main/20241023_000443.jpg)
![cbget](https://github.com/LOBYXLYX/reCaptcha-Reversing/blob/main/20241023_001438.jpg)

```python
import subprocess

r = subprocess.run(
    ['node', 'cb_param.js'],
    capture_output=True,
    text=True
)
cb = r.stdout
print(cb)
```
