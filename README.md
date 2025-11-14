# 🦷 Berrycare iOS App – Smart Oral Screening & Report Upload

Berrycare iOS App is a seamless oral-health screening tool built with **SwiftUI**, **Firebase OTP Login**, **CoreData**, and an integrated **Camera & Upload Framework**.  
Users can log in, fill screening forms, capture mouth images, upload reports securely, and view past screenings all inside one smooth, mobile first experience.

---

## 🚀 Demo Video

▶️ **Watch the Demo**  
https://your-demo-video-link.com

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
| ![](![IMG_5290](https://github.com/user-attachments/assets/06c027e3-737f-464b-8915-c505f665a7e7)
) | ![](![IMG_5291](https://github.com/user-attachments/assets/371e3601-7bf5-4e7f-aef1-495cbd7fc41a)
) | ![](<img width="585" height="1266" alt="IMG_5239 2" src="https://github.com/user-attachments/assets/49355870-f022-4402-8dd0-5f46b2dc432d" />
) |

### 📝 Forms & Camera
| Habit Form | Camera View | Upload Success |
|------------|--------------|----------------|
| ![](screens/habitform.png) | ![](screens/camera.png) | ![](screens/success.png) |

### 📄 Reports & PDF
| Reports | Pending | PDF Viewer |
|---------|----------|-------------|
| ![](screens/reports.png) | ![](screens/pending.png) | ![](screens/pdf.png) |

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
