🎓 倒计时安全版课程助手（CQOOC 专用）

一个用于 重庆高校在线开放课程（cqooc.com） 的浏览器插件
支持视频自动播放 + 非视频页面倒计时自动进入下一节，安全合规、不篡改数据

✨ 功能特性
🎬 视频自动播放
自动识别页面视频并播放
支持倍速播放（默认 3x）
可选静音播放
⏱ 非视频页面自动倒计时
自动识别无视频页面
倒计时结束后自动进入下一节
➡️ 自动跳转下一节
视频播放结束自动进入下一课
倒计时完成自动跳转
🔒 安全设计（核心优势）
❌ 不拦截接口
❌ 不伪造学习进度
❌ 不读取 Cookie
✅ 模拟真实用户行为
🧠 适用场景
在线课程挂机学习
视频课程批量播放
无视频章节自动完成等待
📦 安装方法
方式一：下载 ZIP 安装
点击本仓库 Code → Download ZIP
解压文件
打开 Chrome 浏览器
进入：chrome://extensions/
开启右上角「开发者模式」
点击「加载已解压的扩展程序」
选择解压后的文件夹
⚙️ 使用说明

打开课程页面：

https://www.cqooc.com/course/detail/courseStudy*
插件会自动运行：
有视频 → 自动播放 + 倍速
无视频 → 自动倒计时
完成后自动进入下一节 🎉
🔧 可配置项（Popup）
参数	说明	默认值
enabled	是否启用插件	true
playbackRate	播放倍速	3
muted	是否静音	false
autoNextLesson	自动下一节	true
fallbackWaitSeconds	无视频默认等待时间	20 秒
extraWaitSeconds	额外缓冲时间	1 秒
📁 项目结构
.
├── manifest.json      # 插件配置
├── content.js         # 核心逻辑
├── content.css        # 样式
├── popup.html         # 设置面板
└── popup.js           # 设置逻辑
🛠 技术栈
Chrome Extension (Manifest V3)
JavaScript (Vanilla)
DOM 自动化检测
Chrome Storage API
⚠️ 注意事项

仅适用于：

www.cqooc.com
页面结构变化可能导致功能失效
建议配合正常学习使用
🐛 已知问题
某些页面 DOM 结构变化可能导致按钮识别失败
视频检测依赖页面加载状态，偶尔需要刷新
📌 TODO

支持更多在线课程平台

更智能的章节识别

UI 优化

自动重试机制

🤝 贡献

欢迎提交 Issue / PR！

📄 License

MIT License © 2026

⭐ 支持一下

如果这个项目对你有帮助，欢迎点个 Star ⭐
