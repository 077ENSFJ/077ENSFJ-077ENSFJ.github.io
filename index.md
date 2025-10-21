## FEAGINE ONE

<!-- 视频区域（含顶部文字框） -->
<section style="width: 100vw; margin: 0 calc(-50vw + 50%); padding: 0; background: #000; position: relative;">
  <!-- 居中文字浮层（纯透明背景） -->
  <div style="width: 60%; height: auto; padding: 30px 20px; display: flex; flex-direction: column; justify-content: center; align-items: center; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); z-index: 10; border-radius: 4px;">
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
      <source src="./yifenzhong(xiao).mp4" type="video/mp4">
      <div style="color: white; text-align: center; padding: 100px 20px;">
        <h3>FEAGINE ONE - Origami Manipulator</h3>
        <p>视频加载中...</p>
      </div>
    </video>
  </div>
</section>

<!-- 产品功能介绍区域 -->
<section style="width: 100vw; margin: 0 calc(-50vw + 50%); padding: 80px 20px; background: #000;">
  <h2 style="text-align: center; margin-bottom: 60px; color: white; font-size: 2.5rem;">产品功能介绍</h2>
  
  <!-- 两行共4个视频（每行2个），无容器宽度限制，Grid布局保证均匀间距 -->
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 40px; margin: 0 auto; padding: 0 20px;">
    <!-- 第一个视频及文字 -->
    <div>
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
          <source src="./zishiying（xiao）.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(0,0,0,0.7); text-align: center; color: white; border-radius: 4px;">
        自适应力度抓取
      </div>
    </div>

    <!-- 第二个视频及文字 -->
    <div>
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
          <source src="./keshihua.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(0,0,0,0.7); text-align: center; color: white; border-radius: 4px;">
        可视化运动界面
      </div>
    </div>

    <!-- 第三个视频及文字 -->
    <div>
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
          <source src="./yidongjiaodu.mp4" type="video/mp4">
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(0,0,0,0.7); text-align: center; color: white; border-radius: 4px;">
        机械臂移动范围
      </div>
    </div>

    <!-- 第四个视频及文字（新增） -->
    <div>
      <div style="width: 100%; padding-bottom: 56.25%; position: relative;">
        <video autoplay muted playsinline loop style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; border-radius: 4px;">
          <source src=".moduan yidongsudu/.mp4" type="video/mp4"> <!-- 替换为实际视频路径 -->
        </video>
      </div>
      <div style="margin-top: 20px; padding: 15px; background: rgba(0,0,0,0.7); text-align: center; color: white; border-radius: 4px;">
        末端移动速度
      </div>
    </div>
  </div>
</section>

<style>
  header, footer {
    display: none !important;
  }
</style>