
# yd-lidar-x4-python
Python code for data fetch and real time visualization with the yd-lidar x4 laser scanner.

![Screenshot visualization](/doku/real_time_plot.png)

### pip install requirements.txt

### How To Run:
```sh
$ python main.py
```

### Change Serial Port accordingly:
```python
lidarPort = '/dev/tty.SLAB_USBtoUART'
```

### Note:
At least on OSX 10.12.6 the current (5.15.x) PYQt5 version does not work properly. This is why it was important to go back to PyQt5 version 5.13.0. [Reference](https://forum.qt.io/topic/103273/error-in-my-first-qt5-program)

Python 3.8.2 is used.