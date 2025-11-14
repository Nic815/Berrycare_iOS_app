# 🦷 Berrycare iOS App – Smart Oral Screening & Report Upload

Berrycare iOS App is a seamless oral-health screening tool built with **SwiftUI**, **Firebase OTP Login**, **CoreData**, and an integrated **Camera & Upload Framework**.  
Users can log in, fill screening forms, capture mouth images, upload reports securely, and view past screenings all inside one smooth, mobile first experience.

---

## 🚀 Demo Video

▶️ **Watch the Demo**  


https://github.com/user-attachments/assets/c3238c32-8882-4c07-8c29-65df7e378758



> _Shows OTP login, form filling, camera capture, upload flow, error handling, reports tab, and PDF download._

---

## 📱 Features

### 🔐 Authentication  
- Fast Firebase phone number login  
- OTP verification + backend authentication  
- Dual-token system for secure API calls  

---

### 📝 Smart Forms  
- Habit Screening Form with validation  
- Patient Details Form with CoreData save toast  
- Auto-scroll, tooltips, and Dark/Light mode  
- “Next” button remains disabled until complete  

---

### 📷 Camera Capture & Upload  
- High-quality AVCapture mouth image capture  
- Thumbnail previews  
- Local file-path storage  
- Sequential & reliable image uploading  
- Upload success only if **all** images succeed  
- Error popup with **Retry**  
- Framework delegate returns the user to Home  

---

### 📄 My Reports  
- Uploaded Reports (API + offline caching)  
- Pending Reports (CoreData live updates)  
- Swipe-to-refresh  
- Retry upload per pending screening  
- Re-complete upload for finished reports  
- Auto re-upload incomplete screenings on launch  
- PDF download with loading indicator  

---

## 📸 Screenshots

### 🔐 Authentication Flow
| Login | OTP | Home |
|-------|-----|------|
| <img src="https://github.com/user-attachments/assets/06c027e3-737f-464b-8915-c505f665a7e7" width="250" /> | <img src="https://github.com/user-attachments/assets/371e3601-7bf5-4e7f-aef1-495cbd7fc41a" width="250" /> | <img src="https://github.com/user-attachments/assets/49355870-f022-4402-8dd0-5f46b2dc432d" width="250" /> |


### 📝 Forms & Camera
| Patient Form | Habit Form | Camera View |
|--------------|-------------|-------------|
| <img src="https://github.com/user-attachments/assets/f5405b8c-8332-4f90-a08b-a7597b5819d7" width="250" /> | <img src="https://github.com/user-attachments/assets/beaeec3a-b689-4827-9874-a2d568cad87b" width="250" /> | <img src="https://github.com/user-attachments/assets/c126e2f6-99f3-4a5b-86ae-15733a170a1b" width="250" /> |





### 📄 Reports & Profile
| Reports | Upload Success | Profile |
|---------|----------------|---------|
| <img src="https://github.com/user-attachments/assets/25379d0b-433a-4c62-829b-55d99434c102" width="250" /> | <img src="https://github.com/user-attachments/assets/2c5ead26-6e18-4b08-bf4d-dd9e911b80b2" width="250" /> | <img src="https://github.com/user-attachments/assets/0100aaa9-7881-49b7-9800-c22ea00ec2e8" width="250" /> |


---

## 🛠️ Tech Stack

- SwiftUI  
- MVC + MVVM Hybrid  
- Firebase Phone Auth  
- CoreData (offline-first)  
- Swift Concurrency (async/await)  
- URLSession REST API  
- Integrated Camera & Upload Framework  

---

## 📦 Installation

### 1️⃣ Clone the project
```sh
git clone https://github.com/YourUsername/Berrycare-iOS-App.git
