---
layout: default
---

<style>
.container {
  display: flex;
  gap: 60px;
  width: 100%;
  max-width: 3000px;
  margin: 60px auto;
  align-items: flex-start;
}

.profile {
  flex: 1;
  min-width: 340px;
}

.info {
  flex: 2;
  max-width: 100%;
  line-height: 1.85;
}

.profile img {
  width: 95%;
  height: auto;
  border-radius: 10px;
  margin: 0 auto 18px auto;
  display: block;
}

.profile-intro {
  padding-left: 32px; /* 20px(icon) + 12px(gap) */
  margin-bottom: 30px;
}

/* ===== 아이콘 리스트 ===== */

.icon-list {
  list-style: none;
  padding: 0;
  margin-top: 16px;

  display: flex;
  flex-direction: column;
  gap: 14px;
}

.icon-list li {
  display: flex;
  align-items: baseline;
  line-height: 1.2;
  padding-left: 0;
}
  
.icon-wrapper {
  width: 22px; 
  height: 22px;
  display: flex;
  padding-left: 0;
  justify-content: center;
  align-items: center;
  margin-right: 12px;
}
  
.icon {
  width: 18px !important;
  height: 18px !important;
  border-radius: 0 !important;
  object-fit: contain;
  display: block;
}

.emoji {
  width: 18px;
  text-align: center;
}

.icon-list a {
  color: #0366d6;
  text-decoration: none;
}

.icon-list a:hover {
  text-decoration: underline;
}

/* layout override */
.wrapper,
.page-content {
  max-width: none !important;
}
</style>


<div class="container">

<div class="profile">
  <img src="./images/profile.jpg" alt="profile">
<div class="profile-intro">
    <h3 class="profile-name">Kyutae Kang</h3>
    <p class="profile-desc">
      Mathematics major with interests in Computer Vision and AI.
    </p>
</div>
<ul class="icon-list">
  <li>
    <span class="icon-wrapper">
      <img src="./images/googlemaps.svg" class="icon" alt="Maps">
    </span>
    <span>Seoul, Korea</span>
  </li>
  <li>
    <span class="icon-wrapper">
      <img src="./images/wikiversity.svg" class="icon" alt="Univ">
    </span>
    <span>Kyung Hee University</span>
  </li>

  <li>
  <a
    href="mailto:raymondkang4837@email.com"
    class="icon-wrapper"
  >
    <img src="./images/gmail.svg" class="icon" alt="Email">
  </a>
  <span>Email</span>
</li>

  <li>
  <a
    href="https://github.com/raymondkang4837"
    class="icon-wrapper"
  >
    <img src="./images/github.svg" class="icon" alt="Github">
  </a>
  <span>Github</span>
  </li>

  <li>
  <a
    href="https://azurei.tistory.com/"
    class="icon-wrapper"
  >
    <img src="./images/tistory.svg" class="icon" alt="Blog">
  </a>
  <span>Blog</span>
  </li>
</ul>
</div>


<div class="info" markdown="1">

# **Kyutae Kang**
---
<br>
I am studying Mathematics at KyungHee University, focusing on deep learning and its applications to computer vision. 

I document what I learn on [my blog](https://azurei.tistory.com/) — from concepts to implementation details and failures.


<br><br>

## **Education**
B.S. in Mathematics, Kyung Hee University ( 2020.03 ~ 2026.02 )

GPA: 4.16 / 4.5 ( Major : 4.24 / 4.5 )

Relevant Coursework : 

Numerical Analysis, Differential Geometry, Linear Algebra, Probability Theory, Stochastic Processes, Computational Fluid Dynamics, Optimization, Deep Learning



<br><br>

## **Skills**

Docs, PyTorch, NumPy, Matplotlib, Git

Math: Linear Algebra, PDE, Optimization, Matrix Calculus

![Notion](https://img.shields.io/badge/notion-#000000?style=flat-square&logo=Notion&logoColor=white)


<br><br>

## **Contact**

I’d be happy to talk more — feel free to reach out anytime!

[Email](mailto:your@email.com) / [Github](https://github.com/kyutve) / [Blog](https://azurei.tistory.com/)

</div>
</div>
