Trail 使用须知

1. AI 生成项目声明 / AI-Generated Project Notice

本项目的源代码由 AI 辅助生成。但本工具本身并非 AI 应用：所有数据处理都在你的本地浏览器中完成，我无法获取、收集或存储你上传的任何内容，你的文件和数据绝不会被用于任何形式的 AI 训练。

The codebase of this project was generated with AI tools. However, the tool itself is not an AI application — all processing happens locally in your browser. Nothing you upload is collected, stored, or used for AI training.

2. 以下是可导入的文件，出现漏帧空帧的情况请检查文件名是否正确
├── imgs/
│   ├── stand_a.png
│   ├── left_a1.png ~ left_a24.png
│   ├── right_a1.png ~ right_a24.png
│   ├── up_a1.png ~ up_a24.png
│   ├── down_a1.png ~ down_a24.png
│   ├── idle_a1.png ~ idle_a24.png
│   ├── special1_a1.png ~ special1_a24.png
│   ├── special2_a1.png ~ special2_a24.png
│   ├── click_a1.png ~ click_a24.png
│   ├── encounter_a1.png ~ encounter_a24.png
│   ├── footprint_a.png
│   ├── petleft_a.png
│   ├── petright_a.png
│   ├── stand_b.png
│   ├── left_b1.png ~ left_b24.png
│   ├── right_b1.png ~ right_b24.png
│   ├── up_b1.png ~ up_b24.png
│   ├── down_b1.png ~ down_b24.png
│   ├── idle_b1.png ~ idle_b24.png
│   ├── special1_b1.png ~ special1_b24.png
│   ├── special2_b1.png ~ special2_b24.png
│   ├── click_b1.png ~ click_b24.png
│   ├── encounter_b1.png ~ encounter_b24.png
│   ├── footprint_b.png
│   ├── petleft_b.png
│   └── petright_b.png
└── audio/
    ├── audio_a1.mp3
    ├── audio_a2.mp3
    ├── audio_a3.mp3
    ├── audio_a4.mp3
    ├── audio_b1.mp3
    ├── audio_b2.mp3
    ├── audio_b3.mp3
    └── audio_b4.mp3

文件名           对应动画                        播放时机
audio_a1.mp3    角色1 特殊动画1（special1_a）    角色1 播放特殊动画1 时
audio_a2.mp3    角色1 特殊动画2（special2_a）    角色1 播放特殊动画2 时
audio_a3.mp3    角色1 点击动画（click_a）        点击角色1 时
audio_a4.mp3    角色1 遭遇动画（encounter_a）    触发遭遇动画 a 时
audio_b1.mp3    角色2 特殊动画1（special1_b）    角色2 播放特殊动画1 时
audio_b2.mp3    角色2 特殊动画2（special2_b）    角色2 播放特殊动画2 时
audio_b3.mp3    角色2 点击动画（click_b）        点击角色2 时
audio_b4.mp3    角色2 遭遇动画（encounter_b）    触发遭遇动画 b 时

3. 本程序免费提供使用，严禁任何形式的倒卖。
4. 程序内使用的模板小人由松子老师绘制，允许自由进行二次创作，但禁止用于商业用途。
5. 建议人物处于画布中下位置，程序上是画布中心靠近鼠标指针，画布底部生成足迹。
6. 运行 exe 时，安全软件可能产生误报。将整个文件加入白名单或信任区即可正常运行。
7. 走路动画，待机动画，特殊动画，遭遇动画均最多支持 24 帧。若不足 24 帧，程序会自动跳过空帧，因此无需画满 24 帧。
8. 本程序的开发初衷源自松子老师的提议：希望有一个在使用鼠标时能紧紧跟随、并留下一串脚印的小东西。Trail 由此诞生。愿它能为大家带来一个在桌面上奔跑的小家伙，祝使用愉快。
9. 如遇 bug 或有改进建议，可通过指定渠道反馈。

小红书：27702508865
QQ群：1127568947
邮箱：14236740@qq.com