# 🎬 Netflix Clone — AWS Cloud Streaming Project

A Netflix-style video streaming web application built using **HTML, CSS, JavaScript** and deployed on **AWS Cloud Infrastructure** using **S3 Static Hosting** and **CloudFront CDN**.

This project demonstrates real-world cloud deployment architecture similar to production streaming platforms.

---

## 📌 Project Overview

This project replicates a Netflix-like user interface with cloud-based video delivery.

### Core Highlights:

- Static website hosted on AWS S3  
- Video streaming delivered through CloudFront CDN  
- Optimized performance using edge caching  
- Secure bucket access controlled via CloudFront Origin Access  
- Responsive UI with modal video playback  

---

## 🖥 Application Preview

### 🎨 Netflix Clone UI
<img width="1917" height="867" alt="Screenshot 2026-02-01 222350" src="https://github.com/user-attachments/assets/bb3472e3-8c60-4e2c-bfcd-aa45a08cc682" />

---

### 🗄 AWS S3 Bucket Hosting

<img width="1236" height="785" alt="Screenshot 2026-02-01 205008" src="https://github.com/user-attachments/assets/d5e0f3cd-cb46-46ec-81ca-dadf6ef84666" />

---

## ⚙ Cloud Architecture Diagram

The infrastructure follows modern CDN-based content delivery design:

<img width="1536" height="1024" alt="ChatGPT Image Feb 1, 2026, 11_32_53 PM" src="https://github.com/user-attachments/assets/705c60f3-d9a3-450a-9971-a16e266af814" />


---

## 🔁 Architecture Flow

User Browser
↓
CloudFront (CDN) ← Recommended for streaming
↓
S3 Bucket (Website Files + Videos)


### How It Works:

- User accesses website through CloudFront  
- CloudFront caches files globally  
- Video requests are served from nearest edge location  
- S3 acts as secure origin storage  

This architecture improves:

✅ Performance  
✅ Load speed  
✅ Buffering efficiency  
✅ Scalability  
✅ Security  

---

## 🚀 Features

- Netflix-style homepage UI  
- Modal popup video player  
- CloudFront CDN based streaming  
- AWS S3 static hosting  
- Secure origin configuration  
- Responsive design  
- Optimized performance using caching  
- Mobile friendly layout  

---

## 🛠 Technologies Used

### Frontend

- HTML5  
- CSS3  
- JavaScript  

### Cloud Services

- AWS S3 (Static Website Hosting)  
- AWS CloudFront (CDN)  
- AWS IAM & Bucket Policies  

---

## 🔐 Security Implementation

- Public access blocked on S3  
- CloudFront Origin Access configured  
- Direct S3 object access restricted  
- Only CloudFront allowed to fetch content  

This ensures:

✔ Controlled access  
✔ Reduced attack surface  
✔ Secure content delivery  

---

## 📊 Performance Optimization

CloudFront provides:

- Edge caching  
- HTTP Range Requests (video seek support)  
- Reduced latency  
- Global distribution  
- Faster playback start time  

---

## 📌 Learning Outcomes

Through this project I learned:

- AWS Static Hosting deployment  
- CDN integration using CloudFront  
- Secure bucket policy configuration  
- Real-world streaming architecture  
- Cloud performance optimization  
- Production-style frontend deployment  




## ⭐ If You Like This Project

Give this repository a ⭐ star and feel free to fork or contribute.

Thank you for visiting!
