---
---
 
## FEAGINE ONE

<link rel="stylesheet" href="css/style.css">

<section class="hero-section">
  <div class="hero-video-container">
    <video width="100%" controls autoplay muted playsinline loop class="main-video">
      <source src="./xiaobanben.mp4" type="video/mp4">
      <div style="color: white; text-align: center; padding: 100px 20px;">
        <h3>FEAGINE ONE - Origami Manipulator</h3>
        <p>视频加载中...</p>
      </div>
    </video>
  </div>
</section>

<!-- 产品功能介绍部分 -->
<section class="features-section">
    <h2>产品功能介绍</h2>
    <div class="features-grid">
        <!-- 第一行 -->
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video1.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>智能抓取</p>
            </div>
        </div>
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video2.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>精准定位</p>
            </div>
        </div>
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video3.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>柔性控制</p>
            </div>
        </div>
    </div>

    <!-- 第二行 -->
    <div class="features-grid" style="margin-top: 30px;">
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video4.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>自适应调节</p>
            </div>
        </div>
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video5.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>多场景应用</p>
            </div>
        </div>
        <div class="feature-item">
            <video autoplay muted loop playsinline>
                <source src="./video6.mp4" type="video/mp4">
            </video>
            <div class="feature-caption">
                <p>安全协作</p>
            </div>
        </div>
    </div>
</section>

{% capture text %}
{%
  include button.html
  link="Origami"
  text="Origami Manipulator"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}