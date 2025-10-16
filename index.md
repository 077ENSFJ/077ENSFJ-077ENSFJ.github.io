---
---
 

## Product Category

<!-- 全屏视频区域（含文字浮层） -->
<section style="width: 100vw; height: 100vh; margin: 0; padding: 0; background: #000; position: relative; overflow: hidden;">
  <!-- 16:9 视频容器 -->
  <div style="width: 100%; height: 100%; position: relative;">
    <video 
      autoplay 
      muted 
      playsinline 
      loop 
      style="width: 100%; height: 100%; object-fit: cover; display: block;"
    >
      <source src="xiaobanben.mp4" type="video/mp4">
      <!-- 视频加载失败时的提示 -->
      <div style="color: white; text-align: center; padding: 100px 20px; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);">
        <h3>视频加载失败</h3>
      </div>
    </video>
 
    <!-- 文字浮层（三行居中） -->
    <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); z-index: 10; text-align: center; color: white; width: 100%; max-width: 800px; padding: 0 20px;">
      <div style="font-size: 3rem; font-weight: bold; margin-bottom: 15px;">擎羽科技</div>
      <div style="font-size: 1.2rem; margin-bottom: 8px;">以仿生性操作重构机器人劳动边界</div>
      <div style="font-size: 1.2rem;">专注于柔性机械臂的创新与应用</div>
    </div>
  </div>
</section>

<!-- 产品功能介绍区域 -->
<section style="width: 100vw; margin: 0; padding: 80px 20px; background: #000;">
  <h2 style="text-align: center; margin-bottom: 60px; color: white; font-size: 2.5rem;">产品功能介绍</h2>
  
  <!-- 三视频并列布局 -->
  <div style="display: flex; justify-content: space-between; gap: 30px; max-width: 1800px; margin: 0 auto;">
    <!-- 第一个视频及文字 -->
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="video1.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white; width: 100%;">
        功能介绍1（后续填入内容）
      </div>
    </div>

    <!-- 第二个视频及文字 -->
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="video2.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white; width: 100%;">
        功能介绍2（后续填入内容）
      </div>
    </div>

    <!-- 第三个视频及文字 -->
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;">
          <source src="video3.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(255,255,255,0.1); text-align: center; color: white; width: 100%;">
        功能介绍3（后续填入内容）
      </div>
    </div>
  </div>
</section>
