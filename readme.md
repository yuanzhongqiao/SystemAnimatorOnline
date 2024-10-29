<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9835982" _msthash="415">XR 动画师</h1><a id="user-content-xr-animator" class="anchor" aria-label="永久链接：XR Animator" href="#xr-animator" _mstaria-label="429637" _msthash="416"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="217296053" _msthash="417">在 PC 和 Web 浏览器上使用单个网络摄像头进行全身实时运动跟踪</h3><a id="user-content-full-body-real-time-motion-tracking-with-a-single-webcam-on-your-pc-and-web-browser" class="anchor" aria-label="永久链接：在 PC 和 Web 浏览器上使用单个网络摄像头进行全身实时运动跟踪" href="#full-body-real-time-motion-tracking-with-a-single-webcam-on-your-pc-and-web-browser" _mstaria-label="5255718" _msthash="418"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/ButzYung/SystemAnimatorOnline/raw/master/images/XR_Animator_thumbnail01.png"><img width="640" height="360" title="XR Animator" src="https://github.com/ButzYung/SystemAnimatorOnline/raw/master/images/XR_Animator_thumbnail01.png" style="max-width: 100%;"></a>
</p>
<p dir="auto" _msttexthash="5096347386" _msthash="419">XR Animator 继承自我之前的桌面小工具项目 System Animator，是一款基于视频/网络摄像头的 AI 动作捕捉应用程序，专为 VTubing 和元宇宙时代而设计。它使用 <a href="https://github.com/google/mediapipe" _istranslated="1">MediaPipe</a> 和 <a href="https://github.com/tensorflow/tfjs-models" _istranslated="1">TensorFlow.js</a> 的机器学习 （ML） 解决方案从实时网络摄像头视频中检测 3D 姿势，然后使用该视频驱动 3D 虚拟形象（MMD/VRM 模型），就像您用身体控制它一样。它可用于 VTubing 和各种 XR/3D 用途。</p>
<p dir="auto" _msttexthash="550989127" _msthash="420">它具有多种运动跟踪选项。您可以选择跟踪面部、全身或介于两者之间的内容（面部/身体/手的任意组合）。</p>
<p dir="auto" _msttexthash="3121154036" _msthash="421">Web 应用程序版本适用于桌面和智能手机上的所有主要 Web 浏览器。在同时支持 Web Worker 和 OffscreenCanvas 的浏览器（例如 Chrome）上，它可以在普通的 PC 上实现 60fps 的视觉渲染和 30fps 的身体姿势检测。在处理能力有限的智能手机上，您可能希望限制其在面部跟踪中的使用。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="66060449" _msthash="422">🌐<a href="https://sao.animetheme.com/XR_Animator.html" rel="nofollow" _istranslated="1">XR Animator - Web 应用程序版本</a></h3><a id="user-content-xr-animator---web-app-version" class="anchor" aria-label="永久链接：🌐XR Animator - Web 应用程序版本" href="#xr-animator---web-app-version" _mstaria-label="26718263" _msthash="423"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1120112110" _msthash="424">Windows/Linux 应用程序版本（由 <a href="https://www.electronjs.org/" rel="nofollow" _istranslated="1">Electron</a> 提供支持）也可供下载，它提供了一些仅在本机操作系统环境中可用的额外功能（例如 VMC 协议、透明背景）。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="97674447" _msthash="425">🖥️<a href="https://github.com/ButzYung/SystemAnimatorOnline/releases" _istranslated="1">XR Animator - Windows/Linux 应用程序版本</a></h3><a id="user-content-️xr-animator---windowslinux-app-version" class="anchor" aria-label="永久链接：🖥️XR Animator - Windows/Linux 应用程序版本" href="#️xr-animator---windowslinux-app-version" _mstaria-label="43390490" _msthash="426"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5209451" _msthash="427">特征</h1><a id="user-content-features" class="anchor" aria-label="永久链接：功能" href="#features" _mstaria-label="370552" _msthash="428"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="274022203" _msthash="429">支持使用单个网络摄像头或媒体文件（图像/视频）进行全身 AI 运动跟踪</p>
</li>
<li>
<p dir="auto" _msttexthash="261182415" _msthash="430">支持“完美同步”/ARKit 兼容的 52 种混合形状，实现逼真的面部跟踪</p>
</li>
<li>
<p dir="auto" _msttexthash="76153207" _msthash="431">支持使用任何 MMD/VRM 模型作为您的 3D 头像</p>
</li>
<li>
<p dir="auto" _msttexthash="98077655" _msthash="432">录制动作捕捉动作并将其导出为 BVH 或 VMD 动作格式</p>
</li>
<li>
<p dir="auto" _msttexthash="51639237" _msthash="433">支持加载 VMD/FBX/BVH 格式的 3D 动作</p>
</li>
<li>
<p dir="auto" _msttexthash="44490394" _msthash="434">将 FBX/BVH 运动导出为 VMD 格式</p>
</li>
<li>
<p dir="auto" _msttexthash="250166059" _msthash="435">使用 2D 图像/视频、3D 全景和 3D 对象（.x/.glb 格式）自定义背景和 3D 场景</p>
</li>
<li>
<p dir="auto" _msttexthash="723197566" _msthash="436">支持 VMC 协议，可在其他支持 VMC 的应用程序（如 VSeeFace、Unity 和 Unreal Engine）中的其他位置为 3D 模型制作动画（仅限 Electron 模式）</p>
</li>
<li>
<p dir="auto" _msttexthash="395401578" _msthash="437">在 OBS 等视频捕获应用程序上支持具有透明背景的无框窗口（仅限 Electron 模式）（*）</p>
</li>
<li>
<p dir="auto" _msttexthash="144408758" _msthash="438">在 Android Chrome 浏览器上支持 AR（增强现实）</p>
</li>
</ul>
<p dir="auto" _msttexthash="178952605" _msthash="439">观看这些 <a href="https://youtube.com/playlist?list=PLLpwhHMvOCSt3i7NQcyJq1fFhoMiSmm5H" rel="nofollow" _istranslated="1">YouTube 视频演示</a>并观看 XR Animator 的实际应用！</p>
<p dir="auto" _msttexthash="1244122425" _msthash="440">（*） - 要在没有浏览器 UI 的情况下在 OBS 上捕获 XR Animator 的 Web 应用程序版本，您必须在 OBS 浏览器上打开 XR Animator。OBS 上需要一些额外的命令行参数才能允许相机访问。<a href="https://twitter.com/yeemachine/status/1461908260638785540" rel="nofollow" _istranslated="1">详</a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5674149" _msthash="441">性能</h1><a id="user-content-performance" class="anchor" aria-label="永久链接： 性能" href="#performance" _mstaria-label="473122" _msthash="442"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2486772418" _msthash="443">XR Animator 的系统要求相对较低，因此可在各种设备上使用，包括笔记本电脑甚至智能手机。在配备 GTX1650 级 GPU 的入门级 PC 上运行具有全身动捕功能的 XR Animator，您可以预期姿势/手指跟踪为 20+ fps，面部跟踪为 40+ fps（上限为 30），3D 渲染为 60fps。</p>
<p dir="auto" _msttexthash="2537277730" _msthash="444">但是，如果您使用的是笔记本电脑，但遇到的帧速率低于预期，则应用程序可能使用的集成 GPU 速度较慢。对于笔记本电脑用户来说，这是一个非常普遍的问题。配置您的显卡设置并确保使用更快的专用 GPU。如果您不知道如何操作，请查看下面的文章。</p>
<p dir="auto"><a href="https://techcult.com/how-to-force-windows-to-use-dedicated-graphics/" rel="nofollow" _msttexthash="49147735" _msthash="445">如何强制 Windows 使用专用图形</a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="32356610" _msthash="446">增强现实 （AR）</h1><a id="user-content-augmented-reality-ar" class="anchor" aria-label="永久链接：增强现实 （AR）" href="#augmented-reality-ar" _mstaria-label="779571" _msthash="447"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/ButzYung/SystemAnimatorOnline/raw/master/images/XR_Animator_thumbnail02.png"><img width="720" height="440" title="XR Animator in AR" src="https://github.com/ButzYung/SystemAnimatorOnline/raw/master/images/XR_Animator_thumbnail02.png" style="max-width: 100%;"></a>
</p>
<p dir="auto" _msttexthash="2396944563" _msthash="448">XR Animator 和 System Animator Online 的其他一些演示支持手机上的“增强现实”（AR） 模式，该模式可渲染 3D 模型，使其看起来就像存在于现实世界中一样。AR 模式需要支持 Google ARCore 技术的手机、Chrome 浏览器和新的 WebXR API。请按照以下步骤操作。</p>
<ol dir="auto">
<li>
<p dir="auto" _msttexthash="224923309" _msthash="449"><a href="https://developers.google.com/ar/discover/supported-devices" rel="nofollow" _istranslated="1">在此处查看 ARCore 支持的设备列表</a>，并查看您的设备是否受支持。</p>
</li>
<li>
<p dir="auto" _msttexthash="160227431" _msthash="450">在 Google Play 上安装<a href="https://play.google.com/store/apps/details?id=com.google.ar.core" rel="nofollow" _istranslated="1">适用于 AR 的 Google Play 服务</a> （ARCore）。</p>
</li>
<li>
<p dir="auto" _msttexthash="59196774" _msthash="451">安装适用于 Android 的 Chrome 浏览器。</p>
</li>
</ol>
<p dir="auto" _msttexthash="307852857" _msthash="452">您准备好迎接 AR 体验了吗？在您的 Android Chrome 浏览器上<a href="https://sao.animetheme.com/XR_Animator.html" rel="nofollow" _istranslated="1">查看 XR Animator 的在线版本</a>！</p>
<p dir="auto" _msttexthash="3453644285" _msthash="453">页面完全加载后，点击左上角（或左下角）菜单上的小手机按钮，激活AR模式。启用 AR 模式后，您将看到手机摄像头显示的内容。在要放置 3D 模型的地面上移动相机，此时应出现一个白色圆圈。双击屏幕，3D 模型将放置在白色圆圈上。如果要将模型放置在其他位置，请再次双击 Tab 键以重新召唤白色圆圈。</p>
<p dir="auto" _msttexthash="70892003" _msthash="454"><a href="https://www.youtube.com/playlist?list=PLLpwhHMvOCSt_9k1zDMKHc7X1nBUwnU8l" rel="nofollow" _istranslated="1">查看这些 YouTube 视频</a>进行演示。</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="7193719" _msthash="455">AR 自拍</h1><a id="user-content-ar-selfie" class="anchor" aria-label="永久链接：AR 自拍" href="#ar-selfie" _mstaria-label="348582" _msthash="456"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="746438524" _msthash="457">XR Animator 还支持 AR 自拍功能，同时使用前置摄像头（用于 AR）和自拍摄像头，让您在 AR 模式下使用 3D 虚拟形象进行自拍。</p>
<p dir="auto" _msttexthash="4783107238" _msthash="458">在进入 AR 模式之前，您需要先双击“自拍相机”图标并启用自拍相机。然后，您可以在 AR 会话期间随时切换自拍相机。默认情况下，头像始终以自拍模式显示在您面前。双击“Segmentation AI”图标以启用 AI 模式，该模式会检测您在相机内的形状，让您的头像融入背景并显示在您身后。请注意，AI 模式为 SLOW。您可能需要最新的 Android 手机才能获得流畅的帧速率。</p>
<p dir="auto" _msttexthash="382572099" _msthash="459">您也可以直接在 PC 上使用“Segmentation AI”，并在您身后显示头像，而无需通过 AR 模式。</p>
<p dir="auto" _msttexthash="714896234" _msthash="460">最后，点击 快照 图标，将生成一张静止照片。这可以保存到您的手机中，用于您想要的任何目的，也许可以向您的朋友炫耀！</p>
<p dir="auto" _msttexthash="77195027" _msthash="461"><a href="https://youtu.be/TIMPqV9lVH8" rel="nofollow" _istranslated="1">请观看以下 YouTube 视频</a>进行演示。</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="29173079" _msthash="462">❤️支持此项目</h1><a id="user-content-️support-this-project" class="anchor" aria-label="永久链接： ❤️支持此项目" href="#️support-this-project" _mstaria-label="18296915" _msthash="463"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1968178082" _msthash="464">XR Animator 的未来有赖于您的支持🙇一些 IRL 家庭问题大大增加了我的经济负担。虽然开发该应用程序很有趣，但财务回报几乎微乎其微。现实迫使我评估这个项目的可持续性，否则很快我就不得不放弃了......😢</p>
<p dir="auto" _msttexthash="2559187527" _msthash="465">如果您喜欢 XR Animator，请考虑捐款🙇，或者更好的是，加入我的会员，享受<em _istranslated="1"><strong _istranslated="1">抢先体验最新版本的 XR Animator</strong></em> 等福利（至少在 GitHub 上公开发布前一个月）、内幕故事/提示和其他好处🎁赞助我们，并帮助保持该项目的免费和可持续🙏</p>
<ul dir="auto">
<li _msttexthash="38680811" _msthash="466">☕<a href="https://ko-fi.com/butzyung/tiers" rel="nofollow" _istranslated="1">Ko-fi （会员制）</a></li>
<li _msttexthash="42567278" _msthash="467">🎁<a href="https://xra.fanbox.cc/" rel="nofollow" _istranslated="1">FANBOX （FANBOX）</a></li>
<li _msttexthash="26316238" _msthash="468">☕<a href="https://ko-fi.com/butzyung" rel="nofollow" _istranslated="1">请给我买杯咖啡</a></li>
<li _msttexthash="32203171" _msthash="469">🙏<a href="https://www.paypal.me/AnimeThemeGadgets" rel="nofollow" _istranslated="1">通过 PayPal 捐款</a></li>
</ul>
<p dir="auto" _msttexthash="86091434" _msthash="470">XR Animator 目前由以下人员❤️赞助</p>
<ul dir="auto">
<li><strong _msttexthash="82830514" _msthash="471">NewruGuru、Nymph、Shionay、shion、KuraiNoOni、MShade、Kai、Prajzis、LouLi Lou、Cylan Cade、CoCoNo</strong></li>
<li _msttexthash="16539718" _msthash="472">其他支持单位</li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4287062" _msthash="473">关于 System Animator</h1><a id="user-content-about-system-animator" class="anchor" aria-label="永久链接：关于 System Animator" href="#about-system-animator" _mstaria-label="820456" _msthash="474"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/58597337e4e0f8eb57265f274186b29e3650ae10b26943ba034574ec957c7059/68747470733a2f2f7777772e616e696d657468656d652e636f6d2f736964656261722f73635f736964656261725f30342e6a7067"><img width="720" height="450" title="System Animator" src="https://camo.githubusercontent.com/58597337e4e0f8eb57265f274186b29e3650ae10b26943ba034574ec957c7059/68747470733a2f2f7777772e616e696d657468656d652e636f6d2f736964656261722f73635f736964656261725f30342e6a7067" data-canonical-src="https://www.animetheme.com/sidebar/sc_sidebar_04.jpg" style="max-width: 100%;"></a>
</p>
<p dir="auto" _msttexthash="3116218287" _msthash="475">System Animator 最初是一个桌面小工具项目，诞生于 10 多年前。最新版本 System Animator Online 是一个主要版本改进，专注于作为 Web 应用程序工作，而不仅仅是一个桌面小工具。它完全支持 MikuMikuDance （MMD） 模型和动作，以及最新的 VRM 模型和 FBX/BVH 动作，以创建身临其境的 3D 环境。</p>
<p dir="auto" _msttexthash="1483574027" _msthash="476">很难用几个词来描述 System Animator Online 能做什么。从简单的动画 CPU 仪表到交互式 3D 音乐可视化器，从手机上的简单 AR 小工具到 PC 上的全身运动跟踪应用程序，可能性是无穷无尽的。</p>
<p dir="auto" _msttexthash="292214494" _msthash="477">有关 System Animator 的桌面小工具版本的更多信息，请访问以下页面。<a href="https://www.animetheme.com/sidebar/" rel="nofollow" _istranslated="1">https://www.animetheme.com/sidebar/</a></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="25027704" _msthash="478">📖背景故事</h3><a id="user-content-background-story" class="anchor" aria-label="永久链接：📖背景故事" href="#background-story" _mstaria-label="26146302" _msthash="479"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1310972273" _msthash="480">System Animator 诞生于 10 多年前，作为 Windows Vista 的一个个人的 100 行左右的微型 JavaScript 桌面小工具项目，它将动画火箭动漫女孩显示为 CPU 仪表（动画仍在 XR Animator 中）。</p>
<p dir="auto" _msttexthash="10549577688" _msthash="481">随着时间的推移，我决定添加更多功能，多功能系统仪表、音乐可视化器、3D/MMD 支持、动画壁纸引擎、RPG 引擎，最终您在 XR Animator 中看到的功能。代码库呈指数级增长，而核心仍然是基于 Internet Explorer 的 JavaScript 小工具，事情变得越来越笨拙，以至于我不得不决定是否从头开始重写所有内容以匹配现代编码标准（开源、基于模块等）。然而，我放弃了，决定继续我所写的，因为完全重启需要太多的时间和精力，可能不值得作为个人项目。此外，正如编程规则所说，“如果它有效，就不要碰它”哈哈</p>
<p dir="auto" _msttexthash="3874227526" _msthash="482">最终，为了方便起见，我决定将该项目放在 Github 上，但从技术上讲，您可以认为它是开源的，尽管我不得不承认一些代码已经过时、笨拙且令人困惑。如果您只是 XR Animator/System Animator 作为应用程序的最终用户，一切都很好，但如果您想从我的代码构建自己的东西，请注意，它们可能非常难以理解，哈哈</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="57490576" _msthash="483">基于 System Animator Online 的其他演示</h1><a id="user-content-other-demos-based-on-system-animator-online" class="anchor" aria-label="永久链接：基于 System Animator Online 的其他演示" href="#other-demos-based-on-system-animator-online" _mstaria-label="1907958" _msthash="484"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="170648712" _msthash="485"><a href="https://sao.animetheme.com/" rel="nofollow" _istranslated="1">3D Miku The Dancer</a>（放下任何 MP3，她会为你跳舞）</p>
</li>
<li>
<p dir="auto"><a href="https://sao.animetheme.com/?cmd_line=/TEMP/DEMO/miku_rpg01" rel="nofollow" _msttexthash="41938221" _msthash="486">3D Miku RPG 角色扮演游戏</a></p>
</li>
<li>
<p dir="auto"><a href="https://sao.animetheme.com/?cmd_line=/TEMP/DEMO/miku_battle_arena01" rel="nofollow" _msttexthash="801242" _msthash="487">3D Vocaloid Fighters - Miku vs Teto</a></p>
</li>
<li>
<p dir="auto" _msttexthash="103691146" _msthash="488"><a href="https://sao.animetheme.com/SystemAnimator_online_multiplayer.html" rel="nofollow" _istranslated="1">3D 多人角色扮演游戏</a>（最多 3 名玩家）</p>
</li>
</ul>
<p dir="auto" _msttexthash="1160820427" _msthash="489">所有 Demo 都支持使用自定义 MMD （MikuMikuDance） 模型。在开头放置您最喜欢的 MMD 模型的 zip 文件，按下 START 按钮，演示将继续使用您的模型而不是默认模型。</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="28298829" _msthash="490">版权/许可证/信用</h1><a id="user-content-copyrightlicensecredits" class="anchor" aria-label="永久链接：版权/许可证/信用" href="#copyrightlicensecredits" _mstaria-label="1079143" _msthash="491"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="22793082" _msthash="492">通用许可：</h3><a id="user-content-general-license" class="anchor" aria-label="永久链接：通用许可证：" href="#general-license" _mstaria-label="613509" _msthash="493"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font _mstmutation="1" _msttexthash="41572323" _msthash="494">许可证 （CC BY-NC-SA 4.0） - <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/" rel="nofollow" _mstmutation="1" _istranslated="1">http://creativecommons.org/licenses/by-nc-sa/4.0/</a></font>
<ul dir="auto">
<li _msttexthash="403412750" _msthash="495">如果您出于自己的目的（例如构建其他软件或服务）改编 XR Animator 的源代码，则此许可适用。</li>
<li _msttexthash="192835097" _msthash="496">此许可证不涵盖任何可能具有自己不兼容许可证的第三方资产。</li>
<li _msttexthash="1107550951" _msthash="497">此许可不适用于通过 XR Animator 功能生成的内容，例如使用您自己的资源通过 System Animator 的动作捕捉功能生成的视频内容。XR Animator 对此类内容不主张任何权利或责任。</li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="37102260" _msthash="498">核心应用程序/库：</h3><a id="user-content-core-appslibraries" class="anchor" aria-label="永久链接：核心应用程序/库：" href="#core-appslibraries" _mstaria-label="785070" _msthash="499"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="49059946" _msthash="500">System Animator © Butz Yung/动漫主题 - <a href="http://www.animetheme.com/sidebar/" rel="nofollow" _istranslated="1">http://www.animetheme.com/sidebar/</a></p>
<ul dir="auto">
<li _msttexthash="25114375" _msthash="501">免责声明：<a href="http://www.animetheme.com/system_animator_online/docs/disclaimer.txt" rel="nofollow" _istranslated="1">http://www.animetheme.com/system_animator_online/docs/disclaimer.txt</a></li>
</ul>
</li>
<li>
<p dir="auto"><a href="https://www.electronjs.org/" rel="nofollow" _msttexthash="5161559" _msthash="502">电子</a></p>
</li>
<li>
<p dir="auto"><a href="https://threejs.org/" rel="nofollow" _msttexthash="108303" _msthash="503">three.js</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/pixiv/three-vrm" _msttexthash="2117414" _msthash="504">3 个 VRM</a></p>
</li>
<li>
<p dir="auto" _msttexthash="213397769" _msthash="505"><a href="https://github.com/GrimoireGL/GrimoireJS" _istranslated="1">jThree v2</a> （注意：jThree 已停产。它的继任者被称为“Grimoire.js”）</p>
</li>
<li>
<p dir="auto" _msttexthash="137565792" _msthash="506"><a href="https://github.com/kripken/ammo.js" _istranslated="1">ammo.js，Bullet</a> Physics 到 JavaScript 的移植，zlib 许可</p>
</li>
<li>
<p dir="auto" _msttexthash="64076168" _msthash="507"><a href="https://stuk.github.io/jszip/" rel="nofollow" _istranslated="1">JSZip</a> （在 MIT 许可下使用）</p>
</li>
<li>
<p dir="auto"><a href="https://github.com/google/mediapipe" _msttexthash="12727897" _msthash="508">媒体管道</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/tensorflow/tfjs" _msttexthash="220883" _msthash="509">TensorFlow.js</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/adzialocha/osc-js" _msttexthash="9937499" _msthash="510">OSC-JS 软件</a></p>
</li>
<li>
<p dir="auto"><a href="https://peerjs.com/" rel="nofollow" _msttexthash="5444387" _msthash="511">对等JS</a></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="23051158" _msthash="512">其他第三方资产</h3><a id="user-content-other-third-party-assests" class="anchor" aria-label="永久链接：其他第三方资产" href="#other-third-party-assests" _mstaria-label="1039896" _msthash="513"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><a href="http://3d.nicovideo.jp/alicia/" rel="nofollow" _msttexthash="33845552" _msthash="514">“ニコニ立体ちゃん”3D模型</a></p>
</li>
<li>
<p dir="auto" _msttexthash="108645355" _msthash="515">“Appearance Miku” MMD 模型 - <a href="http://www.animetheme.com/system_animator_online/jThree/model/Appearance%20Miku/Readme.txt" rel="nofollow" _istranslated="1">自述文件/许可证</a></p>
</li>
<li>
<p dir="auto"><a href="http://www.nicovideo.jp/watch/sm11196123" rel="nofollow" _msttexthash="50023103" _msthash="516">ローポリ雑魚敵 by 黒胡椒 さん</a></p>
</li>
<li>
<p dir="auto"><a href="http://www.nicovideo.jp/watch/sm24249428" rel="nofollow" _msttexthash="57313451" _msthash="517">気休めモーション配布 by モコキッカー さん</a></p>
</li>
<li>
<p dir="auto"><a href="http://www.nicovideo.jp/watch/sm29537433" rel="nofollow" _msttexthash="61442654" _msthash="518">格闘シーン簡易作成用モーション by spinach さん</a></p>
</li>
<li>
<p dir="auto" _msttexthash="128962275" _msthash="519">一些纹理/图像/图标源 <a href="https://3dtextures.me/" rel="nofollow" _istranslated="1">https://3dtextures.me/</a> <a href="https://opengameart.org/content/rpg-inventory" rel="nofollow" _istranslated="1">https://opengameart.org/content/rpg-inventory</a> <a href="https://opengameart.org/content/fantasy-icon-pack-by-ravenmore-0" rel="nofollow" _istranslated="1">https://opengameart.org/content/fantasy-icon-pack-by-ravenmore-0</a> <a href="https://opengameart.org/content/potion-bottles" rel="nofollow" _istranslated="1">https://opengameart.org/content/potion-bottles</a> <a href="https://www.flaticon.com/" rel="nofollow" _istranslated="1">https://www.flaticon.com/</a> <a href="https://www.iconfinder.com/" rel="nofollow" _istranslated="1">https://www.iconfinder.com/</a> <a href="https://icon-icons.com/en/pack/Social-Distancing/2274" rel="nofollow" _istranslated="1">https://icon-icons.com/en/pack/Social-Distancing/2274</a> <a href="https://github.com/icons8/flat-color-icons" _istranslated="1">https://github.com/icons8/flat-color-icons</a> <a href="https://www.behance.net/gallery/41818673/FREE-SPORT-ICONS" rel="nofollow" _istranslated="1">https://www.behance.net/gallery/41818673/FREE-SPORT-ICONS</a></p>
</li>
<li>
<p dir="auto"><a href="http://ryntaro-n.anime.coocan.jp/MMD.htm" rel="nofollow" _msttexthash="78661063" _msthash="520">3D 天幕纹理由 Ryntaro Nukata/額田倫太郎</a></p>
</li>
<li>
<p dir="auto" _msttexthash="215315334" _msthash="521">Bleed <a href="https://remusprites.carbonmade.com/" rel="nofollow" _istranslated="1">https://remusprites.carbonmade.com/</a> <a href="https://opengameart.org/content/simple-explosion-bleeds-game-art" rel="nofollow" _istranslated="1">https://opengameart.org/content/simple-explosion-bleeds-game-art</a> 的简单爆炸</p>
</li>
<li>
<p dir="auto"><a href="https://freesound.org/people/RSilveira_88/sounds/216198/" rel="nofollow" _msttexthash="977626" _msthash="522">Cartoon_Punch_02.wav by RSilveira_88</a></p>
</li>
<li>
<p dir="auto" _msttexthash="140213671" _msthash="523">从 <a href="https://www.shadertoy.com/" rel="nofollow" _istranslated="1">Shadertoy</a> 上的代码移植和修改的各种 3D 背景效果</p>
</li>
<li>
<p dir="auto" _msttexthash="45925867" _msthash="524"><a href="https://www.freepik.com/" rel="nofollow" _istranslated="1">Freepik</a> 的一些图标和背景</p>
</li>
<li>
<p dir="auto" _msttexthash="1122770675" _msthash="525">对于 System Animator 中使用的其他一些第三方编程库/3D 数据/资源，请参阅相应的脚本/自述文件以获取许可和条款（可在 System Animator 的可下载/Github 版本上找到）。</p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="69738981" _msthash="526">某些演示中使用的其他第三方资产</h3><a id="user-content-other-third-party-assests-used-in-some-demos" class="anchor" aria-label="永久链接：某些演示中使用的其他第三方资产" href="#other-third-party-assests-used-in-some-demos" _mstaria-label="2029287" _msthash="527"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="48483838" _msthash="528">もぐ式りょう/りく/りょく/りん by Mogg <a href="https://3d.nicovideo.jp/works/td55798" rel="nofollow" _istranslated="1">https://3d.nicovideo.jp/works/td55798</a> <a href="https://3d.nicovideo.jp/works/td55973" rel="nofollow" _istranslated="1">https://3d.nicovideo.jp/works/td55973</a> <a href="https://3d.nicovideo.jp/works/td56074" rel="nofollow" _istranslated="1">https://3d.nicovideo.jp/works/td56074</a> <a href="https://3d.nicovideo.jp/works/td56604" rel="nofollow" _istranslated="1">https://3d.nicovideo.jp/works/td56604</a></p>
</li>
<li>
<p dir="auto" _msttexthash="121511013" _msthash="529">“怪奇物语” - Michael Jobity <a href="https://soundcloud.com/foreignmachine/stranger-remix" rel="nofollow" _istranslated="1">https://soundcloud.com/foreignmachine/stranger-remix</a> 的混音</p>
</li>
<li>
<p dir="auto" _msttexthash="134701632" _msthash="530">龙珠 Super I Ultra Instinct OST I 众神冲突混音 I 嘻哈器乐 I @AndrezoWorks <a href="https://www.youtube.com/watch?v=KJ71dY4mkNo" rel="nofollow" _istranslated="1">https://www.youtube.com/watch?v=KJ71dY4mkNo</a></p>
</li>
<li>
<p dir="auto" _msttexthash="176705698" _msthash="531">感谢 System Animator 中使用的任何其他图像/媒体文件的作者。</p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5992727" _msthash="532">接触</h1><a id="user-content-contacts" class="anchor" aria-label="永久链接：联系方式" href="#contacts" _mstaria-label="370175" _msthash="533"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto" _msttexthash="14088620" _msthash="534">YouTube：<a href="https://www.youtube.com/user/AnimeThemeGadget" rel="nofollow" _istranslated="1">https://www.youtube.com/user/AnimeThemeGadget</a></p>
</li>
<li>
<p dir="auto" _msttexthash="13930423" _msthash="535">推特：<a href="https://twitter.com/butz_yung" rel="nofollow" _istranslated="1">https://twitter.com/butz_yung</a></p>
</li>
<li>
<p dir="auto" _msttexthash="13361270" _msthash="536">无序：<a href="https://discord.gg/Xs4YEMVtkx" rel="nofollow" _istranslated="1">https://discord.gg/Xs4YEMVtkx</a></p>
</li>
<li>
<p dir="auto" _msttexthash="11083007" _msthash="537">Ko-fi：<a href="https://ko-fi.com/butzyung" rel="nofollow" _istranslated="1">https://ko-fi.com/butzyung</a></p>
</li>
<li>
<p dir="auto" _msttexthash="17584970" _msthash="538">粉丝盒： <a href="https://xra.fanbox.cc/" rel="nofollow" _istranslated="1">https://xra.fanbox.cc/</a></p>
</li>
<li>
<p dir="auto" _msttexthash="14387139" _msthash="539">脸书：<a href="https://www.facebook.com/AnimeThemeGadgets/" rel="nofollow" _istranslated="1">https://www.facebook.com/AnimeThemeGadgets/</a></p>
</li>
<li>
<p dir="auto" _msttexthash="57302544" _msthash="540">主页 （System Animator）：<a href="https://www.animetheme.com/sidebar/" rel="nofollow" _istranslated="1">https://www.animetheme.com/sidebar/</a></p>
</li>
<li>
<p dir="auto" _msttexthash="22204182" _msthash="541">电子邮件： <a href="mailto:webmaster@animetheme.com" _istranslated="1">webmaster@animetheme.com</a></p>
</li>
</ul>
</article></div>
