# Teaching

<!-- 导航栏（可放入 <body> 最上方） -->
<nav id="navbar">
  <div class="nav-container">
    <div class="nav-title"><a href="index.html">Jie Ling</a></div>
    <div class="nav-links">
      <a href="index.html">Home</a>
      <a href="Detailed profile.html">Profile</a>
      <a href="projects.html">Projects</a>
      <a href="teaching.html">Teaching</a>
      <a href="publications.html">Publications</a>
      <a href="students.html">Students</a>
      <a href="contact.html">Contact</a>
    </div>
  </div>
</nav>

<!-- 样式 -->
<style>
  #navbar {
    position: sticky;
    top: 0;
    z-index: 999;
    background: #ffffff;
    border-bottom: 1px solid #ddd;
    box-shadow: 0 2px 4px rgba(0,0,0,0.04);
    font-family: 'Segoe UI', sans-serif;
  }

  .nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1080px;
    margin: auto;
    padding: 12px 20px;
  }

  .nav-title a {
    font-size: 20px;
    font-weight: bold;
    color: #00558C;
    text-decoration: none;
  }

  .nav-links a {
    margin-left: 20px;
    text-decoration: none;
    color: #444;
    font-weight: 500;
    position: relative;
    transition: color 0.3s ease;
  }

  .nav-links a:hover {
    color: #007acc;
  }

  .nav-links a::after {
    content: '';
    position: absolute;
    width: 0%;
    height: 2px;
    background-color: #007acc;
    left: 0;
    bottom: -4px;
    transition: width 0.3s ease;
  }

  .nav-links a:hover::after {
    width: 100%;
  }

  @media screen and (max-width: 768px) {
    .nav-container {
      flex-direction: column;
      align-items: flex-start;
    }

    .nav-links {
      margin-top: 10px;
      display: flex;
      flex-wrap: wrap;
    }

    .nav-links a {
      margin: 6px 12px 0 0;
    }
  }
</style>



## 📘 Undergraduate Courses 本科生课程

- **液压与气压传动**  
  *Hydraulic and Pneumatic Transmission*

- **可编程控制器**  
  *Programmable Logic Controller (PLC)*

- **机器人动力学与控制**  
  *Robot Dynamics and Control*

---

## 🎓 Master's and Doctoral Courses 研究生课程

- **基于智能材料的机电系统：建模与控制**  
  *Modelling and Control of Smart Materials-based Mechatronic Systems*  
  🧭 *NUAA International Course*  
  🤝 *Joint with [Prof. Micky Rakotondrabe](http://m.rakoton.net/) from [UTTOP](https://www.uttop.fr/en/index.html), France*

- **学术读写说技巧**  
  *Academic Reading, Writing and Presentation Skills*  
  🧭 *NUAA International Course*  
  🤝 *Joint with [Prof. Micky Rakotondrabe](http://m.rakoton.net/) ([UTTOP](https://www.uttop.fr/en/index.html)), France*

---
