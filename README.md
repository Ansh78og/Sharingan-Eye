# 🌀 Sharingan Eye Tracker  
### 💻 Coded by Ansh  

---

## ⚡ Overview  
The **Sharingan Eye Tracker** is a real-time computer vision project that brings the iconic **Sharingan** from *Naruto* to life using **OpenCV** and **MediaPipe**.  
It detects your face through your webcam and animates **two glowing Sharingan eyes** that follow your movement.  

This project beautifully combines **AI-based face tracking** with **anime-inspired VFX**, creating a mesmerizing and interactive visual effect.

---

## 🎥 Demo Preview  
> *(Add your demo video or GIF here)*  
> Example:  
> ![Demo](demo.gif)

---

## 🧠 Features  
- 👁️ **Real-Time Face Tracking** – Detects and tracks your face live using MediaPipe.  
- 🔴 **Dynamic Sharingan Animation** – Pupils follow your head movement.  
- 🔄 **Rotating Tomoe Effect** – Realistic, continuously rotating tomoe around each pupil.  
- 🌌 **Cinematic Visuals** – Layered background and transparent overlays for a rich look.  
- ⚙️ **Smooth Motion Control** – Adjustable sensitivity for eye movement.  
- 💫 **Glow and Depth Effects** – Glowing gradients for a 3D feel.  

---

## 🧩 Technologies Used  

| Technology | Purpose |
|-------------|----------|
| **Python 3.x** | Core programming language |
| **OpenCV (cv2)** | Camera input, drawing shapes, and image rendering |
| **MediaPipe** | Real-time face detection |
| **NumPy** | Mathematical calculations for pupil movement |
| **Math & Time** | Used for smooth rotations and glowing animations |

---

## 🗂️ Project Structure  
📦 Sharingan-Eye
┣ 📜 sharingan.py
┣ 🖼️ shh.jpg # Background image
┣ 🖼️ top.png # Transparent overlay image
┣ 📄 requirements.txt
┗ 📘 README.md

yaml
Copy code

---

## 🚀 How It Works  
1. The webcam captures live video frames.  
2. **MediaPipe** detects the user’s face in real-time.  
3. The pupils move according to the detected face position.  
4. **OpenCV** draws the Sharingan eyes with glowing effects and rotating tomoe.  
5. The final output appears as a real-time animated Sharingan window titled **“SHARINGAN AI 👁️👁️”**.  

---

## ⚙️ Installation Steps  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Ansh78og/Sharingan-Eye.git
cd Sharingan-Eye
2️⃣ Install Required Libraries
bash
Copy code
pip install opencv-python mediapipe numpy
3️⃣ Add Your Assets
Place your shh.jpg (background) and top.png (overlay) inside the same folder as sharingan.py.

4️⃣ Run the Program
bash
Copy code
python sharingan.py
🧾 Output Description
When you move your face in front of the webcam:

The Sharingan pupils follow your face direction.

Three tomoe rotate around the pupil, continuously spinning.

The red glow creates a powerful anime-like effect.

You can exit the program anytime by pressing the ESC key.

🧠 Core Concepts Used
Face Detection: MediaPipe’s Face Detection model for tracking.

Coordinate Mapping: Converts face position into smooth pupil movement.

Trigonometric Rotation: Animates tomoe spinning using sine and cosine.

Alpha Blending: Combines transparent overlays seamlessly.

Dynamic Frame Rendering: Refreshes visuals in real-time with every frame.

💡 Example Code Snippet
python
Copy code
# 🌀 Sharingan Eye Tracker
# Coded by Ansh

cv2.imshow("SHARINGAN AI 👁️👁️", eye_img)
This line displays the animated Sharingan interface that updates continuously as your webcam captures new frames.

🖤 Inspiration
Inspired by the Sharingan from Naruto, this project visualizes the power of anime eyes through modern AI and computer vision.
It represents creativity, coding, and motion working together — turning imagination into interactive art.

👨‍💻 Developer
Ansh Gala
🎓 B.Tech CSE (AI, ML & Robotics) – DIT University, Dehradun
🎥 Video Editor • 💻 Developer • 🎨 VFX Designer

🔗 GitHub: Ansh78og
🔗 LinkedIn: Add your profile link here

⭐ Contribute
Contributions are welcome!
Feel free to fork the repository and add your own features like:

🌀 New eye designs (Rinnegan, Mangekyō, Byakugan)

🔧 Improved tracking accuracy

🎨 Enhanced visual effects

🪶 License
This project is open-source and available under the MIT License.
You’re free to use, modify, and share it with proper credit.

🌟 “Awaken the Sharingan — through code.”
yaml
Copy code

---

Would you like me to **add GitHub badges (Python version, license, stars, etc.)** and make it look even more professional like a top open-source repo?






You said:
GIVE ME A FULL FILEW


ChatGPT said:

Analyzed
python
Always show details

Copy code
# Create a README.md file for Ansh's Sharingan Eye Tracker project

readme_content = """# 🌀 Sharingan Eye Tracker  
### 💻 Coded by Ansh  

---

## ⚡ Overview  
The **Sharingan Eye Tracker** is a real-time computer vision project that brings the iconic **Sharingan** from *Naruto* to life using **OpenCV** and **MediaPipe**.  
It detects your face through your webcam and animates **two glowing Sharingan eyes** that follow your movement.  

This project beautifully combines **AI-based face tracking** with **anime-inspired VFX**, creating a mesmerizing and interactive visual effect.

---

## 🎥 Demo Preview  
> *(Add your demo video or GIF here)*  
> Example:  
> ![Demo](demo.gif)

---

## 🧠 Features  
- 👁️ **Real-Time Face Tracking** – Detects and tracks your face live using MediaPipe.  
- 🔴 **Dynamic Sharingan Animation** – Pupils follow your head movement.  
- 🔄 **Rotating Tomoe Effect** – Realistic, continuously rotating tomoe around each pupil.  
- 🌌 **Cinematic Visuals** – Layered background and transparent overlays for a rich look.  
- ⚙️ **Smooth Motion Control** – Adjustable sensitivity for eye movement.  
- 💫 **Glow and Depth Effects** – Glowing gradients for a 3D feel.  

---

## 🧩 Technologies Used  

| Technology | Purpose |
|-------------|----------|
| **Python 3.x** | Core programming language |
| **OpenCV (cv2)** | Camera input, drawing shapes, and image rendering |
| **MediaPipe** | Real-time face detection |
| **NumPy** | Mathematical calculations for pupil movement |
| **Math & Time** | Used for smooth rotations and glowing animations |

---

## 🗂️ Project Structure  
📦 Sharingan-Eye
┣ 📜 sharingan.py
┣ 🖼️ shh.jpg # Background image
┣ 🖼️ top.png # Transparent overlay image
┣ 📄 requirements.txt
┗ 📘 README.md

yaml
Always show details

Copy code

---


## 🚀 How It Works  
1. The webcam captures live video frames.  
2. **MediaPipe** detects the user’s face in real-time.  
3. The pupils move according to the detected face position.  
4. **OpenCV** draws the Sharingan eyes with glowing effects and rotating tomoe.  
5. The final output appears as a real-time animated Sharingan window titled **“SHARINGAN AI 👁️👁️”**.  

---


## ⚙️ Installation Steps  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Ansh78og/Sharingan-Eye.git
cd Sharingan-Eye
2️⃣ Install Required Libraries
bash
Always show details

Copy code
pip install opencv-python mediapipe numpy
3️⃣ Add Your Assets
Place your shh.jpg (background) and top.png (overlay) inside the same folder as sharingan.py.

4️⃣ Run the Program
bash
Always show details

Copy code
python sharingan.py
🧾 Output Description
When you move your face in front of the webcam:

The Sharingan pupils follow your face direction.

Three tomoe rotate around the pupil, continuously spinning.

The red glow creates a powerful anime-like effect.

You can exit the program anytime by pressing the ESC key.

🧠 Core Concepts Used
Face Detection: MediaPipe’s Face Detection model for tracking.

Coordinate Mapping: Converts face position into smooth pupil movement.

Trigonometric Rotation: Animates tomoe spinning using sine and cosine.

Alpha Blending: Combines transparent overlays seamlessly.

Dynamic Frame Rendering: Refreshes visuals in real-time with every frame.

💡 Example Code Snippet
python
Always show details

Copy code
# 🌀 Sharingan Eye Tracker
# Coded by Ansh

cv2.imshow("SHARINGAN AI 👁️👁️", eye_img)
This line displays the animated Sharingan interface that updates continuously as your webcam captures new frames.

🖤 Inspiration
Inspired by the Sharingan from Naruto, this project visualizes the power of anime eyes through modern AI and computer vision.
It represents creativity, coding, and motion working together — turning imagination into interactive art.

👨‍💻 Developer
Ansh Gala
🎓 B.Tech CSE (AI, ML & Robotics) – DIT University, Dehradun
🎥 Video Editor • 💻 Developer • 🎨 VFX Designer

🔗 GitHub: Ansh78og
🔗 LinkedIn: Add your profile link here

⭐ Contribute
Contributions are welcome!
Feel free to fork the repository and add your own features like:

🌀 New eye designs (Rinnegan, Mangekyō, Byakugan)

🔧 Improved tracking accuracy

🎨 Enhanced visual effects

🪶 License
This project is open-source and available under the MIT License.
You’re free to use, modify, and share it with proper credit.

