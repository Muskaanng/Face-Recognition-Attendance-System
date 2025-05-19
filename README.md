# 🎭 Face Recognition Attendance System 📸  

## 🌟 Overview  
Welcome to the **Face Recognition-based Attendance System**! 🎉 This system automates attendance marking using **real-time facial recognition**. Say goodbye to manual entries and enjoy a seamless, secure, and efficient way to track attendance! ✅  

## 🚀 Features  
✅ **Real-time Face Detection** – Captures and processes video from the camera 🎥  
✅ **Automated Attendance Logging** – Matches faces with database records & logs attendance 📝  
✅ **Database Integration** – Stores student details and attendance records securely 💾  
✅ **Audio Feedback** – Beeps when a face is recognized 🎵🔔  
✅ **Optimized Performance** – Uses face encoding for efficient recognition ⚡  

## 🛠️ How It Works  
1️⃣ **Loads student data** (IDs & images) from the database 📂  
2️⃣ **Encodes faces** from stored images 🖼️➡️🧠  
3️⃣ **Captures live video** and extracts face encodings 🎥👀  
4️⃣ **Compares live faces** with stored encodings 🤖🔍  
5️⃣ **Marks attendance** in the database if a match is found ✅📋  
6️⃣ **Displays live video feed** with real-time processing ⚡  

## 🖥️ Installation & Setup  
1️⃣ **Clone the repository** 🛠️  
```bash
git clone https://github.com/Muskaanng/FaceRecognitionAttendance.git
cd FaceRecognitionAttendance
```
2️⃣ **Install dependencies** 📦  
```bash
pip install opencv-python face-recognition mysql-connector-python
```
3️⃣ **Configure the database** 🗄️  
   - Update **DBConnection.py** with your MySQL credentials 🔑  
4️⃣ **Run the script** 🚀  
```bash
python CAMERA.py
```

## 🎯 Future Enhancements  
✨ **Cross-platform compatibility** (replace `winsound` for macOS/Linux)  
✨ **Web/App Integration** for remote access 📱  
✨ **Cloud Database Support** for scalability ☁️  

## 💡 Why Use This System?  
🚀 **Fast & Efficient** – No more manual attendance!  
🔐 **Secure** – Only registered faces can mark attendance.  
🖥️ **Easy to Use** – Simple setup and intuitive interface.  

