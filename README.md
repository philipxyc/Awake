# Awake
Keep your windows PC awake by a super simple python script

```
import ctypes
ctypes.windll.kernel32.SetThreadExecutionState(0x80000002)
input('Press to exit')
ctypes.windll.kernel32.SetThreadExecutionState(0x80000000)
```
