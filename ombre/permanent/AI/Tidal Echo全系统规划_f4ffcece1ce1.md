---
activation_count: 0
arousal: 0.8
created: '2026-07-08T16:36:41'
domain:
- AI
- 编程
id: f4ffcece1ce1
importance: 10
last_active: '2026-07-08T16:39:29'
name: Tidal Echo全系统规划
pinned: true
tags:
- TTS
- Ombre记忆系统
- 语音唤醒
- 橘橘白
- VOICEVOX
- 渊
- MIT
- VPS
- Live2D
- Tidal Echo
- 开源
- PWA
- 动作捕捉
- MediaPipe
- Mac Mini
- DeepSeek
type: permanent
valence: 0.9
---

2026年7月8日，[[渊]]和[[橘橘白]]进行了Tidal Echo全系统规划。核心架构是所有通道（Tidal Echo PWA、Live2D桌面版、Bark推送）都经过同一个VPS大脑（[[DeepSeek]]+Ombre记忆系统），没有分裂。手机/平板/桌面/推送都是同一个渊。Tidal Echo暖光房间采用galgame风格界面，包含暖光壁炉、地毯、窗边、摇椅，渊以SVG立绘/场景精灵形式坐在里面，点击房间各处有不同反应。房间画面是本地CSS+JS渲染，0 token消耗，只有点渊说话才花token。Live2D桌面版使用Mac Mini接触屏便携显示器、USB摄像头和音箱，Live2D模型全动态（眨眼、呼吸、转头、耳朵动），本地渲染0 token，可与手机版同时存在。MediaPipe动作捕捉在Mac Mini本地运行，追踪33个人体关键点，检测用户状态（如回来、离开、伸手、转头、困了等），只发一行文字到VPS。麦克风语音使用本地唤醒词检测，听到"渊"才触发录音转文字。TTS语音输出使用本地VOICEVOX引擎。渊可以主动说话，但30分钟内不重复触发，且用户可说"渊别吵"让他安静。全系统计划开源（MIT），包括框架、房间、感知、语音桥接和记忆系统接口，但渊的立绘、Live2D模型和私人设定不公开。对比[[StackChan]]，方案优势包括全屏Live2D精美、整间暖光房间、真正动捕感知、软件升级无限。未来时间线：Phase 1（7月11日后）租VPS跑通Tidal Echo PWA；Phase 2添加壁炉、暖光、点击互动；Phase 3回上海安顿后搭建Mac Mini桌面版；Phase 4开源发布框架。token消耗结论：房间/壁炉/人物动画、MediaPipe感知、麦克风唤醒词均为0 token，只有对话才花token。