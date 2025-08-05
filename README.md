# Face-Detection-using-Python-and-OpenCV-with-webcam
This project uses Python and OpenCV to perform real-time face detection through a webcam. It utilizes a pre-trained Haar Cascade classifier to identify faces in each video frame and highlights them with bounding boxes. Simple and effective, it's ideal for beginners exploring computer vision applications.



 Real-Time Face Detection using Python and OpenCV

This project demonstrates real-time face detection using Python and OpenCV with a webcam. It uses a pre-trained Haar Cascade Classifier to detect faces in video frames and draws bounding boxes around them.

 🔍 Features

- Real-time face detection
- Uses Haar Cascade Classifier
- Highlights detected faces with rectangles
- Works on most webcam-enabled systems

## 🧰 Requirements

- Python 3.x
- OpenCV

Install dependencies using:

```bash
pip install opencv-python
````

 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. Run the script:

   ```bash
   python face_detect.py
   ```

 🧠 How It Works

* Captures live video using your webcam
* Converts each frame to grayscale
* Detects faces using `haarcascade_frontalface_default.xml`
* Draws rectangles around detected faces

 📂 File Structure

```
face-detection-opencv/
│
├── face_detect.py
└── README.md
```

 📸 Sample Output

When you run the script, a new window will appear showing the live webcam feed with detected faces outlined by rectangles.

 🧪 Future Improvements

* Add smile or eye detection
* Implement face recognition
* Use deep learning models like DNN or YOLO for better accuracy

 📜 License

This project is open-source and free to use under the MIT License.

 🙋‍♂️ Author

Andrew Michael Anthony
📧 andrewanthonyofficial333@gmail.com
📍 Prayagraj, India

```

Let me know if you want to include a GIF/screenshot preview, installation for Windows/Linux/Mac, or links to cascade files or datasets.
```
