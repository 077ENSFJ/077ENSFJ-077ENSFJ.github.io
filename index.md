## FEAGINE ONE

<!-- 视频区域（含顶部文字框） -->
<section style="width: 100vw; margin: 40px calc(-50vw + 50%); padding: 0; background: #000; position: relative;">
  <!-- 居中文字浮层（20%透明黑背景，替代原三个分散框） -->
  <div style="width: 60%; /* 控制浮层宽度 */ height: auto; padding: 30px 20px; display: flex; flex-direction: column; justify-content: center; align-items: center; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); z-index: 10; background: rgba(0,0,0,0.2); /* 20%透明黑背景 */ border-radius: 4px;">
    <!-- 突出显示“擎羽科技” -->
    <div style="margin-bottom: 15px; text-align: center; color: white; font-size: 1.8rem; font-weight: bold; letter-spacing: 2px;">
      擎羽科技
    </div>
    <!-- 下方两行文字依次排列 -->
    <div style="margin-bottom: 10px; text-align: center; color: white; font-size: 1.1rem;">
      以仿生柔性操作重构机器人的劳作边界
    </div>
    <div style="text-align: center; color: white; font-size: 1.1rem;">
      专注于柔性机械臂的创新与应用
    </div>
  </div>

  <!-- 16:9比例视频区域 -->
  <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
    <video 
      controls 
      autoplay 
      muted 
      playsinline 
      loop
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: contain; display: block; border-radius: 4px;"
    >
      <source src="./xiaobanben.mp4" type="video/mp4">
      <div style="color: white; text-align: center; padding: 100px 20px;">
        <h3>FEAGINE ONE - Origami Manipulator</h3>
        <p>视频加载中...</p>
      </div>
    </video>
  </div>
</section>

<!-- 按钮区域 -->
<div style="text-align: center; margin: 40px 0;">
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
  {{ text }}
</div>

<!-- 产品功能介绍区域 -->
<section style="width: 100vw; margin: 40px calc(-50vw + 50%); padding: 80px 20px; background: #000;">
  <h2 style="text-align: center; margin-bottom: 60px; color: white; font-size: 2.5rem;">产品功能介绍</h2>
  
  <!-- 三个并列短视频 -->
  <div style="display: flex; justify-content: space-between; gap: 30px; max-width: 1800px; margin: 0 auto;">
    <!-- 第一个视频及文字 -->
    <div style="flex: 1;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="./video1.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white;">
        功能介绍1（后续填入内容）
      </div>
    </div>

    <!-- 第二个视频及文字 -->
    <div style="flex: 1;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="./video2.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white;">
        功能介绍2（后续填入内容）
      </div>
    </div>

    <!-- 第三个视频及文字 -->
    <div style="flex: 1;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="./video3.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white;">
        功能介绍3（后续填入内容）
      </div>
    </div>
  </div>
</section>