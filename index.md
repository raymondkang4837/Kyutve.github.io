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

.profile h3 {
  margin-bottom: 12px;
  font-size: 1.25rem;
  font-weight: 600;
}

.profile p {
  line-height: 1.7;
  margin-bottom: 14px;
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
  align-items: center;
}
  
.icon-wrapper {
  width: 22px;               
  display: flex;
  justify-content: center;
  align-items: center;
  margin-right: 12px;
}
.icon-wrapper.emoji {
  font-size: 18px;
  line-height: 1;
}
  
.icon {
  width: 18px !important;
  height: 18px !important;
  object-fit: contain;
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

  <h3>Kyutae Kang</h3>
  <p>I major in Mathematics 📏 and have interest in Computer Vision</p>

<ul class="icon-list">
  <li>
    <span class="icon-wrapper">
      <img src="./images/googlemaps.svg" class="icon" alt="Maps">
    </span>
    <span>Seoul, Korea</span>
  </li>

  <li>
    <span class="icon-wrapper emoji">🏦</span>
    <span>Kyung Hee University</span>
  </li>

  <li>
    <span class="icon-wrapper">
      <img src="./images/gmail.svg" class="icon" alt="Email">
    </span>
    <a href="mailto:raymondkang4837@email.com">Email</a>
  </li>

  <li>
    <span class="icon-wrapper">
      <img src="./images/github.svg" class="icon" alt="GitHub">
    </span>
    <a href="https://github.com/raymondkang4837" target="_blank" rel="noopener noreferrer">
      GitHub
    </a>
  </li>

  <li>
    <span class="icon-wrapper">
      <img src="./images/tistory.svg" class="icon" alt="Blog">
    </span>
    <a href="https://azurei.tistory.com/" target="_blank">Blog</a>
  </li>
</ul>
</div>


<div class="info" markdown="1">

# Kyutae Kang

I am studying Mathematics at KyungHee University, focusing on deep learning and its applications to computer vision. 

I document what I learn on [my blog](https://azurei.tistory.com/) — from concepts to implementation details and failures.

---
<br><br>

## **Education**

**B.S. in Mathematics,** Kyung Hee University ( 2020.03 ~ 2026.02 )

GPA: 4.16 / 4.5 ( Major : 4.24 / 4.5 )

Relevant Coursework : 

Numerical Analysis, Differential Geometry, Linear Algebra, Probability Theory, Stochastic Processes, Computational Fluid Dynamics, Optimization, Deep Learning

---

<br><br>

## **Skills**

**Docs**, PyTorch, NumPy, Matplotlib, Git

**Math:** Linear Algebra, PDE, Optimization, Matrix Calculus

---

<br><br>

## **Contact**

I’d be happy to talk more — feel free to reach out anytime!

[Email](mailto:your@email.com) / [Github](https://github.com/kyutve) / [Blog](https://azurei.tistory.com/)

</div>
</div>
