---
layout: default
title: ""
---

<style>
/* 전체 컨테이너 간격 확장 */
/* 레이아웃 전체 */
.container {
  display: flex;
  gap: 60px;
  width: 100%; 
  max-width: 3000px;       /* 페이지 전체 폭 확장 */
  margin: 60px auto;
  align-items: flex-start; /* 위 정렬 */
}

/* 프로필은 고정 크기 */
.profile {
  flex: 1px;         /* 고정 폭 */
  min-width: 340px;
}

/* 본문 영역은 나머지 공간 전부 사용 */
.info {
  flex: 2;                 /* 남은 영역 전부 차지 */
  max-width: 100%;         /* 넓게 확장 */
  line-height: 1.85;
}
/* 프로필 이미지 정렬 + 크기 */
.profile img {
  width: 95%;
  height: auto;
  border-radius: 10px;
  margin: 0 auto 18px auto;
  display: block;
}
/* 프로필 텍스트 간격 재정비 */
.profile h3 {
  margin-bottom: 12px;
  font-size: 1.25rem;
  font-weight: 600;
}

.profile p, .profile ul {
  line-height: 1.7;
  margin-bottom: 14px;
}


h1 {
  margin-top: 0;
  margin-bottom: 10px;
  font-weight: 700;
}

.contact a {
  text-decoration: none;
  color: #0366d6;
}

.wrapper,
.page-content {
  max-width: 100 !important;
}
</style>


<div class="container">

<div class="profile">
  <img src="./images/profile.jpg" alt="profile"> <!-- 프로필 이미지 경로 -->
  <h3>Kyutae Kang</h3>
  <p>I major in Mathematics 📏 and have interest in Computer Vision</p>
  <ul style="list-style:none; padding:0; line-height:1.8; margin-top:15px;">
  <li>📍 Seoul, Korea</li>
    <li>🏦 Kyung Hee University</li>
    <li>📧 <a href="mailto:raymondkang4837@email.com">email</a></li>
    <li>🐱 <a href="https://github.com/raymondkang4837" target="_blank">GitHub</a></li>
    <li>🏡 <a href="https://azurei.tistory.com/" target="_blank">Blog</a></li>
  </ul>
</div>


<div class="info" markdown="1">

# Kyutae Kang

I am studying Mathematics at KyungHee University, focusing on deep learning and its applications to computer vision. 

I document what I learn on [my blog](https://azurei.tistory.com/) — from concepts to implementation details and failures.

---
<br><br>

## **📃Education**

**B.S. in Mathematics,** Kyung Hee University ( 2020.03 ~ 2026.02 )

GPA: 4.16 / 4.5 ( Major : 4.24 / 4.5 )

Relevant Coursework : 

Numerical Analysis, Differential Geometry, Linear Algebra, Probability Theory, Stochastic Processes, Computational Fluid Dynamics, Optimization, Deep Learning

---

<br><br>

## **🛠 Skills**

**Python**, PyTorch, NumPy, Matplotlib, Git

**Math:** Linear Algebra, PDE, Optimization, Matrix Calculus

---

<br><br>

## **Contact**

I’d be happy to talk more — feel free to reach out anytime!

✉️ [Email](mailto:your@email.com)

🐱  [Github](https://github.com/kyutve)

🏠 [Blog](https://azurei.tistory.com/)

</div>
</div>
