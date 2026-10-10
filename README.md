<style>
  /* ═══════════════════════════════════════════
     ANIMATIONS — additive only, original content preserved
     ═══════════════════════════════════════════ */

  @keyframes gradientShift {
    0%   { background-position: 0% 50%; }
    50%  { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  @keyframes floaty {
    0%, 100% { transform: translateY(0px); }
    50%      { transform: translateY(-14px); }
  }

  @keyframes pulseGlow {
    0%, 100% { box-shadow: 0 0 0 0 rgba(0, 247, 255, 0.75); }
    70%      { box-shadow: 0 0 0 14px rgba(0, 247, 255, 0); }
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(28px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  @keyframes borderRun {
    0%   { background-position: 0% 50%; }
    100% { background-position: 200% 50%; }
  }

  /* Animated gradient headline text */
  .grad-text {
    background: linear-gradient(90deg, #00F7FF, #0A66C2, #6A00FF, #00F7FF);
    background-size: 300% 300%;
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientShift 6s ease infinite;
    font-weight: 800;
  }

  .float   { animation: floaty 5s ease-in-out infinite; }
  .pulse   { animation: pulseGlow 2.2s infinite; border-radius: 6px; }
  .fade-up { animation: fadeUp 0.9s ease both; }

  .d1 { animation-delay: 0.15s; }
  .d2 { animation-delay: 0.30s; }
  .d3 { animation-delay: 0.45s; }
  .d4 { animation-delay: 0.60s; }

  /* Hover lift + neon glow on cards, badges, images */
  .lift {
    transition: transform .35s cubic-bezier(.2,.8,.2,1),
                box-shadow .35s ease,
                filter .35s ease;
  }
  .lift:hover {
    transform: translateY(-8px) scale(1.03);
    box-shadow: 0 12px 40px rgba(0, 247, 255, .45),
                0 0 0 1px rgba(0, 247, 255, .35);
    filter: brightness(1.12);
  }

  /* Animated running border for the "Open to Work" badge */
  .border-run {
    background: linear-gradient(90deg, #00F7FF, #0A66C2, #6A00FF, #00F7FF);
    background-size: 200% 200%;
    animation: borderRun 3s linear infinite;
    padding: 3px;
    border-radius: 8px;
    display: inline-block;
  }
</style>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Rajesh+R;Java+Backend+Developer;Spring+Boot+%7C+Microservices+%7C+REST+APIs;Building+Scalable+Backend+Systems;Clean+Code+%7C+Secure+APIs+%7C+Real+Impact"/>
<br/>

<p>
<a href="mailto:rayudurajesh2001@gmail.com">
<img class="lift" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/rajesh-r-9920r8843">
<img class="lift" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/RAJESH">
<img class="lift" src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</p>

<p>
<img class="lift" src="https://komarev.com/ghpvc/?username=RAJESH&color=00F7FF&style=for-the-badge"/>
<span class="border-run"><img src="https://img.shields.io/badge/OPEN%20TO%20WORK-Backend%20Engineering-0A66C2?style=for-the-badge&logo=checkmarx&logoColor=white"/></span>
</p>

</div>

<br/>

<img class="float" align="right" width="340" src="https://raw.githubusercontent.com/rajathkumarmp/rajathkumarmp/master/assets/developer.gif"/>

## <span class="grad-text">👨‍💻 About Me</span>

I'm a **Java Backend Developer** who designs and builds secure, scalable, high-performance backend systems.

I like turning ideas into reliable software — clean architecture, solid data modeling, and production-grade code are what I care about most.

**What I work with**
- 🚀 Building RESTful APIs with **Java & Spring Boot**
- 🔐 Securing applications with **Spring Security & JWT**
- ⚙️ Designing systems with **Microservices Architecture**
- 🗄️ Modeling and optimizing relational & NoSQL databases
- 🧩 Writing clean, testable, maintainable code

**Currently exploring**
- 🌐 Distributed Systems
- ☁️ Cloud-Native Development
- 🏗️ System Design
- ⚡ Performance Optimization

<br clear="right"/>

---

## <span class="grad-text">🛠️ Tech Stack</span>

<div align="center">

**Languages**
<br/>
<img class="lift" src="https://skillicons.dev/icons?i=java"/>

**Backend**
<br/>
<img class="lift" src="https://skillicons.dev/icons?i=spring,hibernate,maven,gradle"/>

**Databases**
<br/>
<img class="lift" src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis"/>

**Tools & Platforms**
<br/>
<img class="lift" src="https://skillicons.dev/icons?i=docker,git,github,linux,postman,aws"/>

</div>

---

## <span class="grad-text">🚀 What I Build</span>

<table>
<tr>
<td width="50%" valign="top">

### 🔥 Backend Engineering
- Java & Spring Boot services
- REST API design
- JPA / Hibernate data layers
- Database query optimization

</td>
<td width="50%" valign="top">

### 🔐 Application Security
- JWT-based authentication
- Role-based authorization
- Secure API design
- Access control & validation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚡ Performance
- Query & index tuning
- API response time improvements
- Scalable service design

</td>
<td width="50%" valign="top">

### 🏗️ Architecture
- Microservices
- Design patterns
- Clean architecture principles
- Distributed systems fundamentals

</td>
</tr>
</table>

---

## <span class="grad-text">🌟 Featured Projects</span>

### 🔐 [SecureHub](https://github.com/RAJESH) — Microservices Security Platform
A backend security platform managing authentication, authorization, and secure inter-service communication.

- JWT-based authentication
- Spring Security integration
- Role-based access control
- Secure service-to-service communication

`Java` `Spring Boot` `Spring Security` `JWT` `Docker` `MySQL`

---

### 🛒 [E-Commerce Backend System](https://github.com/RAJESH) — Scalable Commerce Platform
A backend application for managing products, users, orders, and transactions.

- Product & inventory management
- User authentication
- Order processing pipeline
- Payment integration & transaction handling

`Java` `Spring Boot` `JPA` `MySQL` `REST API`

---

### 🌍 [Tourism Management System](https://github.com/RAJESH) — Booking & Access Platform
A backend platform for managing tourism services with secure, role-based user access.

- Full CRUD operations
- Authentication & authorization
- Centralized exception handling
- Structured logging

`Java` `Spring Boot` `Hibernate`

---

## <span class="grad-text">📊 GitHub Analytics</span>

<div align="center">

<img class="lift" height="180em" src="https://github-readme-stats.vercel.app/api?username=RAJESH&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img class="lift" height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RAJESH&layout=compact&theme=tokyonight&hide_border=true"/>

<br/>

<img class="lift" src="https://github-readme-streak-stats.herokuapp.com/?user=RAJESH&theme=tokyonight&hide_border=true"/>

<br/>

<img class="lift" width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=RAJESH&theme=tokyo-night&hide_border=true&area=true"/>

<br/>

<img class="lift" src="https://github-profile-trophy.vercel.app/?username=RAJESH&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=6"/>

</div>

---

## <span class="grad-text">🏆 Achievements & Certifications</span>

- 🏅 **Java Full Stack Development** — JSpiders
- 🏅 **Java Programming Certification** — Skill Dezire
- ⭐ Built secure REST APIs following industry best practices
- ⭐ Developed backend modules using the modern Java ecosystem

---

## <span class="grad-text">📚 Development Philosophy</span>

> "Great software isn't only about making things work — it's about building systems that are reliable, scalable, and maintainable."

---

## <span class="grad-text">🤝 Let's Connect</span>

I'm always open to:
- Backend development opportunities
- Open-source collaboration
- Software engineering discussions

<div align="center">

<a href="mailto:rayudurajesh2001@gmail.com">
<img class="lift" src="https://img.shields.io/badge/Let's%20Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://linkedin.com/in/rajesh-r-9920r8843">
<img class="lift" src="https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br/><br/>

**🚀 Java · Spring Boot · Microservices · Backend Engineering**

</div>
