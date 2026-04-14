<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ron Royce Tillaman | E-Portfolio</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #eef2f7, #d9e4f5);
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #2c3e50, #4a69bd);
      color: white;
      padding: 50px 20px 40px;
      text-align: center;
    }

    .profile-pic {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 5px solid white;
      object-fit: cover;
      margin-bottom: 15px;
      box-shadow: 0 8px 18px rgba(0,0,0,0.25);
    }

    header h1 {
      margin: 0;
      font-size: 34px;
    }

    header p {
      margin-top: 8px;
      font-size: 16px;
      opacity: 0.95;
    }

    
    .social-icons {
      margin-top: 12px;
    }
    .social-icons a {
      margin: 0 8px;
      display: inline-block;
    }
    .social-icons img {
      width: 32px;
      height: 32px;
      transition: transform 0.2s ease;
    }
    .social-icons img:hover {
      transform: scale(1.2);
    }

    .container {
      max-width: 900px;
      margin: 30px auto;
      padding: 20px;
    }

    section {
      background: white;
      padding: 22px;
      margin-bottom: 20px;
      border-radius: 14px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.08);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    section:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 22px rgba(0,0,0,0.12);
    }

    h2 {
      color: #2c3e50;
      margin-top: 0;
    }

    ul {
      padding-left: 20px;
      line-height: 1.6;
    }


    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      cursor: pointer;
      transition: transform 0.2s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }

    .modal {
      display: none;
      position: fixed;
      z-index: 999;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.8);
      justify-content: center;
      align-items: center;
    }
    .modal img {
      max-width: 90%;
      max-height: 90%;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.3);
    }
    .modal:target {
      display: flex;
    }

    .buttons a {
      display: inline-block;
      margin-right: 10px;
      margin-top: 10px;
      padding: 10px 18px;
      background: #4a69bd;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 14px;
      transition: background 0.2s ease, transform 0.2s ease;
    }
    .buttons a:hover {
      background: #2c3e50;
      transform: translateY(-2px);
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #555;
    }
  </style>
</head>

<body>

  <header>
    <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
    <h1>Ron Royce Tillaman</h1>
    
    <div class="social-icons">
      <a href="https://www.facebook.com/WonWoys" target="_blank">
        <img src="icons/facebook.png" alt="Facebook">
      </a>
      <a href="https://www.instagram.com/wonwoys/" target="_blank">
        <img src="icons/instagram.png" alt="Instagram">
      </a>
      <a href="www.tiktok.com/@r0yceeeee" target="_blank">
        <img src="icons/tiktok.png" alt="TikTok">
      </a>
    </div>
  </header>

  <div class="container">

    <section>
      <h2>About Me</h2>
      <p>
        I am a 4th year college student taking Bachelor of Science in Computer Engineering at 
        Western Institute of Technology. I have hands-on experience in programming languages 
        such as C++, Python, Java, HTML, and CSS, along with familiarity in development tools 
        and platforms including Visual Studio Code, MySQL, and AutoCAD. 
        
        Beyond academics, I enjoy drawing and playing mobile games, which allow me to express creativity, 
        maintain balance, and stay inspired. I am motivated to grow as a professional in the 
        field of computer engineering, combining my technical skills with creativity and 
        problem-solving to contribute effectively to any project or team.
      </p>
    </section>
    
    <section> 
      <h2>Projects and Activities</h2>
      <ul>
        <li>1. ------</li>
        <li>2. ------</li>
      </ul>
    </section> 

    <section>
      <h2>Certificates Gallery</h2>
      <div class="gallery">
        
        <a href="#cert1"><img src="certificates/cert1.jpg" alt="Certificate 1"></a>
        <a href="#cert2"><img src="certificates/cert2.jpg" alt="Certificate 2"></a>
        <a href="#cert3"><img src="certificates/cert3.jpg" alt="Certificate 3"></a>
        <a href="#cert4"><img src="certificates/cert4.jpg" alt="Certificate 4"></a>
        <a href="#cert5"><img src="certificates/cert5.jpg" alt="Certificate 5"></a>
        <a href="#cert6"><img src="certificates/cert6.jpg" alt="Certificate 6"></a>
        <a href="#cert7"><img src="certificates/cert7.jpg" alt="Certificate 7"></a>
        <a href="#cert8"><img src="certificates/cert8.jpg" alt="Certificate 8"></a>
        <a href="#cert9"><img src="certificates/cert9.jpg" alt="Certificate 9"></a>
        <a href="#cert10"><img src="certificates/cert10.jpg" alt="Certificate 10"></a>
        <a href="#cert11"><img src="certificates/cert11.jpg" alt="Certificate 11"></a>
        
      </div>

      
      <div id="cert1" class="modal"><a href="#!" style="width:100%;height:100%;display:flex;justify-content:center;align-items:center;"><img src="certificates/cert1.jpg" alt="Certificate 1"></a></div>
      <div id="cert2" class="modal"><a href="#!"><img src="certificates/cert2.jpg" alt="Certificate 2"></a></div>
      <div id="cert3" class="modal"><a href="#!"><img src="certificates/cert3.jpg" alt="Certificate 3"></a></div>
      <div id="cert4" class="modal"><a href="#!"><img src="certificates/cert4.jpg" alt="Certificate 4"></a></div>
      <div id="cert5" class="modal"><a href="#!"><img src="certificates/cert5.jpg" alt="Certificate 5"></a></div>
      <div id="cert6" class="modal"><a href="#!"><img src="certificates/cert6.jpg" alt="Certificate 6"></a></div>
      <div id="cert7" class="modal"><a href="#!"><img src="certificates/cert7.jpg" alt="Certificate 7"></a></div>
      <div id="cert8" class="modal"><a href="#!"><img src="certificates/cert8.jpg" alt="Certificate 8"></a></div>
      <div id="cert9" class="modal"><a href="#!"><img src="certificates/cert9.jpg" alt="Certificate 9"></a></div>
      <div id="cert10" class="modal"><a href="#!"><img src="certificates/cert10.jpg" alt="Certificate 10"></a></div>
      <div id="cert11" class="modal"><a href="#!"><img src="certificates/cert11.jpg" alt="Certificate 11"></a></div>
    </section>

    <section>
      <h2>Resume and Application Letter</h2>
      <div class="buttons">
        <a href="resume.pdf" target="_blank">Download Resume</a>
        <a href="application-letter.pdf" target="_blank">Download Application Letter</a>
      </div>
    </section>

    <section>
      <h2>Contact Information</h2>
      <p>Email: landayao.christinetcpe1996@email.com</p>
      <p>Phone Number: 09911521772</p>
      <p>Location: Barotac Viejo, Iloilo, Philippines</p>
    </section>

  </div>

  <footer>
    © 2026 Ron Royce Tillaman | E-Portfolio
  </footer>

</body>
</html>
<p align="center">
  <i>Click below to verify credentials:</i><br>
  <a href="INSERT_LINK_HERE">View Credential 1</a> | <a href="INSERT_LINK_HERE">View Credential 2</a>
</p>

---

## 🛠️ Tech Stack & Skills
![Python](https://shields.io)
![C++](https://shields.io)
![Git](https://shields.io)
![Arduino](https://shields.io)

---

## 📊 GitHub Stats
![Your GitHub stats](https://vercel.app[YOUR_USERNAME]&show_icons=true&theme=radical)

---

## 📬 Connect with Me
[![LinkedIn](https://shields.io)]([YOUR_LINKEDIN_URL](https://www.instagram.com/r0yceeeee?igsh=MTFmdWQyMDJ3OGg0NA%3D%3D&utm_source=qr))
[![Facebook](https://shields.io)]([YOUR_FACEBOOK_URL](https://facebook.com/YOUR_FB_LINK))

---
*“Art is the journey of a free soul.”*
📍 Based in Iloilo, Philippines  
📧 Email: tillaman.ronroycedcpe1996@gmail.com  



