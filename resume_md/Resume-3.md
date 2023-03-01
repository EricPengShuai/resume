 <center>
     <h1>彭 帅</h1>
     <div>
         <span>
             <img src="../assets/phone-solid.svg" width="18px">
             17801051728
         </span>
         ·
         <span>
             <img src="../assets/envelope-solid.svg" width="18px">
             pengshuai@bupt.edu.cn
         </span>
         <br>
         <span>
             <img src="../assets/3-gender.svg" width="18px">
             男
         </span>
         ·
         <span>
             <img src="../assets/6-birth.svg" width="18px">
             24
         </span>
         ·
         <span>
             <img src="../assets/4-home.svg" width="18px">
             湖北
         </span>
         ·
         <span>
             <img src="../assets/5-location.svg" width="18px">
             北京
         </span>
         ·
         <span>
             <img src="../assets/github-brands.svg" width="18px">
             <a href="https://github.com/EricPengShuai">ericps</a>
         </span>
         ·
         <span>
             <img src="../assets/rss-solid.svg" width="18px">
             <a href="https://ericpengshuai.github.io/">My Blog</a>
         </span>
     </div>
 </center>

## <img src="../assets/graduation-cap-solid.svg" width="30px"> 教育经历

- **硕士**：北京邮电大学，计算机科学与技术专业，**2021.09~2024.06**
  - 研究方向：虚拟现实与流媒体传输技术，用户视野预测

- **学士**：北京邮电大学，计算机科学与技术专业，**2017.09~2021.06**
  - GPA：3.66/4，88.96/100，年级前 15%，通过了 CET6 (544) 英语等级考试

## <img src="../assets/tools-solid.svg" width="30px"> 个人技能

- **编程语言**：熟悉 C/C++，了解 Python/Golang/JavaScript 等
- **开发工具**：熟悉 Linux 开发环境，有 Git 团队合作工具的经验
- **知识储备**：了解计算机网络：TCP/IP协议栈，操作系统：进程管理，数据库：索引等
- **流媒体相关**：了解 RTMP、RTSP/RTP、HLS、DASH 等流媒体协议，FLV 封装格式，FFmpeg 推流转码等

## <img src="../assets/project-diagram-solid.svg" width="30px"> 项目经历

- **电信未来网络关键技术项目**

  *流媒体传输，单组播协同，RTMP服务器，RTP传输，FLV 封装格式，HTTP-FLV，QUIC*

  - 项目需求：未来网络关键技术项目主要针对直播场景中单组播协同传输进行优化，直播源推送RTMP流到云端节点，云端节点通过RTP组播方式分发至各个边缘节点，边缘节点提供 HTTP-FLV 服务供客户端访问，云端节点缓存 FLV 数据，并和边缘节点通过QUIC通信（quic-go），边缘节点检测到掉包是通过 QUIC 请求重传。
  - 项目职责：本人主要负责云端接收 rtmp 流并提取 rtmp chunk 数据组装成 flvTag，然后**封装成 RTP 包**组播发送，以及维护缓存 RTP 数据包功能的内容队列；边缘节点维护 RTP 数据包的接收队列，利用**滑动窗口**的思想通过序列号检测重传。

- **HUAWEI 新媒体项目**

  *全景视频传输，深度学习，视野预测，码率自适应，缓存调度*

  - 项目需求：新媒体项目主要针对虚拟现实场景，设计一套完整的全景视频传输系统，结合视野预测和码率自适应技术优化传输带宽，通过聚类缓存调度策略降低传输时延。
  - 项目职责：本人在其中主要负责**视野预测**模块，设计深度神经网络仿真测试预测结果并通过 Flask 框架部署网络模型提供 API，结合 A-Frame 和 Angular 前端播放界面进行交互。后端通过 gunicorn 增加并发量，经过 wrk 压测 QPS 为 150 左右，较提升之前 QPS 为 20。
  - 研究成果：基于此发表期刊1篇：**Peng S**, Hu J, Xiao H, et al. Viewport-Driven Adaptive 360° Live Streaming Optimization Framework[J]；CCF-B 会议论文1篇：Wang M, **Peng S**, Chen X, et al. CoLive: An Edge-Assisted Online Learning Framework for Viewport Prediction in 360° Live Streaming[C]//2022 ICME. IEEE, 2022: 1-6.

## <img src="../assets/2-award.svg" width="30px"> 荣誉奖项

- 2021年及2022年北京邮电大学一等学业奖学金
- 第十六届北京邮电大学程序设计竞赛银奖
- 2022年研创《基于深度学习的全景视频传输系统》二等奖
- 2022年计算机学院优秀研究生
- 2021年北京邮电大学优秀本科毕业生
- 2019年及2020年国家励志奖学金
- 2019年北京邮电大学优秀学生干部
- 2018年北京邮电大学二等奖学金

## <img src="../assets/info-circle-solid.svg" width="30px"> 自我评价

- 扎实勤干：善于沟通，责任心强，积极主动，有良好团队合作能力  
- 自学钻研：对新技术一直保持好奇心，探索 GitHub 技术仓库，具有良好的自主学习能力
- 总结反思：学习中通过撰写 [CSDN博客](https://blog.csdn.net/Miracle_ps?type=blog) 和 [MyBlog](https://ericpengshuai.github.io/) 形成自己的知识库，持续反思不断提升





