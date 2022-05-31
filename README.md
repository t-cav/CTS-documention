`⚠️ Windows computers only`
# CTS Documention

An overview of the process for setting up CTS controllers to connect and output data onto a computer. </br>


## Table of Contents
1. Packages & Installations
2. Visual Studio .NET Visualizer
3. Connection to Socket
4. Pygame Demos
5. Pynput Keyboard Control

---

### 1. Packages & Installations
- [Visual Studio](https://visualstudio.microsoft.com/downloads/) (2019 or 2022)
- [Python](https://www.python.org/downloads/)
- [Pygame](https://www.pygame.org/download.shtml)
or run: `python3 -m pip install -U pygame --user`</br>
- [Pynput](https://pypi.org/project/pynput/#files)

---

### 2. Visual Studio .NET Visualizer

Step-by-Step:
  1. Plug CTS controller into computer
  2. Open Arduino file called BLANK
  3. Make sure ports are set up correctly and upload Ardunio code to board
  4. Go to Visual Studio and open BLANK project folder
  5. Open BLANK file
  6. Make sure the port number is correctly assigned:
```
This is going to be some example code
```

---

### 3. Connection to Socket

Step-by-Step:
  1. Open Visual Studio BLANK project folder
  2. Run BLANK file
  3. Open `socket.py` file which uses the following to make a connection & recive data:
  ```
  This is going to be some example code
  ```
  5. No data on first try, run again
  6. When input data is skewed
    - reflash the device by uploading the Arduino sketch again
---

### 4. Pygame Demos

---

### 5. Pynput Keyboard Control


---
