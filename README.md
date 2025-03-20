<p align="center">
  <img id="profile-pic" src="https://github.com/iUtsa/Project-1-Stats/blob/main/Stats-Library/Results/8EFD2ECE-1977-493A-97C3-2B6B9EB6B6DD.png?raw=true" width="150" height="auto">
</p>

<h1 align="center">Hi, I'm Arnab Das Utsa 👋</h1>

<p align="center">
  🎓 Computer Science Student | 💻 AI & ML Enthusiast | 🚀 Software Developer  
</p>

<p align="center">
  <a href="https://iutsa.vercel.app"><img src="https://img.shields.io/badge/Website-iUtsa-blue?style=for-the-badge&logo=Google-Chrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/arnab-das-utsa-0b57a81a4/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/iUtsa"><img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github"></a>
  <a href="mailto:utsaa@go.stockton.edu"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://buymeacoffee.com/iutsa"><img src="https://img.shields.io/badge/BuyMeACoffee-Fuel_My_Coding-orange?style=for-the-badge&logo=buy-me-a-coffee"></a>
</p>

---
## ☕ BUY ME A COFFEE  
[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-Fuel_My_Coding-yellow?style=for-the-badge&logo=buy-me-a-coffee)](https://buymeacoffee.com/iutsa)

or visit: [buymeacoffee.com/iutsa](https://buymeacoffee.com/iutsa)

---

## 👨‍💻 About Me  

I am a **passionate computer science student** at **Stockton University** with a deep love for **software development, AI/ML, and innovative technology**. I enjoy working on **web and mobile applications, exploring cloud computing**, and contributing to **open-source projects**.  

Beyond coding, I engage in **research, tutoring, student leadership, and community service**. I also enjoy **playing musical instruments, photography, and traveling**.

---

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iUtsa&show_icons=true&theme=radical" width="50%">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iUtsa&layout=compact&theme=radical" width="40%">
</p>

---

## 📬 Contact Me

<p align="center">
  <a href="mailto:utsaa@go.stockton.edu"><img src="https://img.shields.io/badge/Email-utsaa@go.stockton.edu-red?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/arnab-das-utsa-0b57a81a4/"><img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://iutsa.vercel.app"><img src="https://img.shields.io/badge/Website-Portfolio-orange?style=for-the-badge&logo=Google-Chrome&logoColor=white"></a>
  <a href="https://buymeacoffee.com/iutsa"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-Fuel_My_Coding-yellow?style=for-the-badge&logo=buy-me-a-coffee"></a>
</p>

---

⭐ **If you like my work, consider giving my repositories a star!** 😊  
🚀 **Let’s build and innovate together!**

---

## 🎨 JavaScript Effects  

To add **interactive movement**, include this in your website version of the README:

```javascript
// Floating effect for profile image
document.addEventListener("DOMContentLoaded", function () {
    let profilePic = document.getElementById("profile-pic");
    let direction = 1;
    let position = 0;

    setInterval(() => {
        if (position >= 10) direction = -1;
        if (position <= -10) direction = 1;
        position += direction;
        profilePic.style.transform = `translateY(${position}px)`;
    }, 50);
});

// Smooth hover effect for badges
document.querySelectorAll("a img").forEach((img) => {
    img.addEventListener("mouseover", () => {
        img.style.transform = "scale(1.1)";
        img.style.transition = "transform 0.2s";
    });
    img.addEventListener("mouseleave", () => {
        img.style.transform = "scale(1)";
    });
});
