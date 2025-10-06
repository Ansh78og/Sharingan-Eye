
# Sharingan Eye - Real-Time Face Tracking Animation 🔴

The **Sharingan Eye** project brings anime-style visual effects to real life using Python and OpenCV. It tracks your face in real time and overlays a glowing Sharingan animation on your eyes, creating a dynamic illusion as if your eyes have truly awakened the Sharingan!


## ✨ Features

- 🎥 Real-time face and eye tracking using OpenCV  
- 🔴 Animated Sharingan overlay that follows your eyes smoothly  
- 💫 Custom glowing effects for realism  
- 🧠 Intelligent tracking with Haar Cascades or MediaPipe (configurable)  
- 🖼️ Adjustable design for different Sharingan types (Itachi, Sasuke, Madara)  
- ⚡ Smooth frame updates for lag-free performance  


## 🧠 Tech Stack

- **Python 3.10** - MUST FOR USE IT MALFUNTIONS ON 3.12 SOMETIMES
- **OpenCV** – for face and eye tracking  
- **NumPy** – for matrix operations  
- **MediaPipe** – for advanced facial landmarks  
- **Custom PNG overlays** – for the Sharingan textures  

## ⚙️ How It Works

1. The webcam captures live video frames.  
2. OpenCV detects the face and eyes in each frame.  
3. The Sharingan overlay image is positioned and scaled over your eyes.  
4. The program updates the display in real time, creating a seamless animated effect.  
5. You can replace the default Sharingan PNG with your favorite version for customization.


## 🧩 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Ansh78og/Sharingan-Eye.git
   cd Sharingan-Eye
   pip install opencv-python numpy
   python sharingan.py

## 🗂️ Project Structure

   ```bash
   Sharingan-Eye/
   │
   ├── .git/ # Git configuration folder
   ├── README.md # Project documentation
   ├── sharingan.py # Main Python script
   ├── shh.jpg # Background or overlay image
   └── top.png # Sharingan eye texture.


      

