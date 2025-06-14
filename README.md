

# 🎨 Virtual Paint App Using Hand Gestures

This Python project is a fun and interactive **virtual paint application** that uses **hand tracking** to let users draw shapes, lines, and freehand sketches on the screen — completely touch-free using your **webcam and hand gestures**!


## ✨ Features

- Select tools with finger gestures
- Draw freehand, lines, rectangles, and circles
- Erase by moving your hand
- Built using **MediaPipe**, **OpenCV**, and **NumPy**
- Real-time performance with gesture-based switching


## 🛠️ Built With

- [MediaPipe](https://google.github.io/mediapipe/) – Hand tracking and landmark detection
- [OpenCV](https://opencv.org/) – Real-time video and drawing
- [NumPy](https://numpy.org/) – Image mask processing



## 📦 Installation

1. **Install Python 3.6+**  
   Make sure Python is installed on your machine.

2. **Install Required Libraries**

```bash
pip install mediapipe opencv-python numpy
````



## 🚀 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/virtual-paint-app.git
cd virtual-paint-app
```

2. **Place the Tool Image**
   Make sure you have a file named `tools.png` in the same folder as `virtual_paint_app.py`.
   This is the image that contains the tool icons (draw, line, circle, rectangle, erase).

3. **Run the Application**

```bash
python virtual_paint_app.py
```

4. **Use Your Hand to:**

   * Hover and wait on a tool to select it
   * Draw with the index finger raised
   * Select shapes by gesture and release to draw
   * Erase by hovering over drawn items



## 🎯 Hand Gestures Guide

| Tool          | Gesture / Area                        |
| ------------- | ------------------------------------- |
| **Draw**      | Select from top toolbar, index up     |
| **Line**      | Select from toolbar, draw and release |
| **Circle**    | Select and draw with distance         |
| **Rectangle** | Select and drag to draw               |
| **Erase**     | Use thumb/index to move eraser        |



## 📸 Notes

* Works best with good lighting and a clear background
* Only one hand is tracked at a time
* Make sure your webcam is accessible
