# codex娘 · ChatGPT 虚拟宠物

基于 [ZipZipPipe 发布的 codex娘设定图（第三张）](https://www.bilibili.com/opus/1238613841710940181)进行的 AI 辅助 Q 版改绘与动画适配。非 OpenAI 官方角色或官方发布。

![坐着写代码](preview/coding-still.png)

![拖拽与挥手预览](preview/changes-preview.gif)

## 动作

| 状态 | 表现 |
| --- | --- |
| 待机 | 坐着使用电脑、写代码 |
| 开始思考 | 暂停打字，挠头思考 |
| 欢迎 / 悬停互动 | 手臂持续举起，左右挥手 |
| 左右拖拽 | 同一套拱背前倾、双手双脚下垂的动作 |
| 等待 / 受阻 / 待查看 | 对应的坐姿表情动作 |
| 视线 | 十六方向观察 |

动作触发与持续时间由 ChatGPT 客户端控制；动画资源不会改变客户端逻辑。思考动作并不保证持续到整轮任务结束。

## 文件与使用

- [完整透明动画图集](assets/spritesheet.png)：v2，1536 × 2288，8 列 × 11 行，每格 192 × 208。
- [全部状态预览](preview/all-states.gif) · [视频预览](preview/all-states.mp4)
- 每行有效帧数：`6, 8, 8, 4, 5, 8, 6, 6, 6, 8, 8`。
- 图集是宠物资源文件，不是独立桌面程序，也不是可执行安装包。

在支持自定义宠物的 ChatGPT / Work 环境中，将 `assets/spritesheet.png` 作为现有宠物图集提供，并明确要求按现成图集导入、保留所有帧，名称设为“codex娘”，不要重新生成。实际导入能力以所用客户端及其宠物工具为准。

## 来源与许可

角色参考：[ZipZipPipe 发布的 codex娘设定图（第三张）](https://www.bilibili.com/opus/1238613841710940181)。感谢原作分享。

本项目按 **[CC BY-NC-SA 4.0（署名—非商业性使用—相同方式共享）](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans)** 分享。使用或继续二创时，请保留来源署名与许可链接、注明改动，仅作非商业用途，并按同一协议分享改编作品。

完整来源与改动说明见 [CREDITS.md](CREDITS.md)，许可说明见 [LICENSE.md](LICENSE.md)。

本项目使用 AI 辅助生成与处理图像，并进行动画整理、验证和客户端适配。ChatGPT / Codex 名称及相关标识属于相应权利人，本项目不表示官方背书。
