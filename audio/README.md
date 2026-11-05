# Observatory / 观测室

三个 Ogg 文件为本项目原创程序编配的同步循环声部，MP3 是带首尾淡变的独立试听版。配乐无原片采样、无外部录音、无人声。

源谱及合成：`scripts/render-audio.mjs`；音效合成：`src/audio.ts`。
生成数据：`score.json`。随项目采用仓库 LICENSE。

## 逐字输入短音

`typing-preview.wav` 及 `src/typing-samples.ts` 已替换为本项目合成的按键音（不含第三方音源）。

提取脚本：`scripts/extract-typing-audio.mjs`。原片短音仅去直流、做边缘淡变和统一增益，没有变调、变速或合成替换。`reference/typing-original.wav` 为本地对照片段，不属于生产配乐。
