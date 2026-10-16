# 奶蛙 Codex 桌宠 🐸

一只鲜黄色、头顶电脑的奶蛙，陪你一起工作。

## 各位小伙伴们下载前可以点个star⭐吗！非常感谢！

## 下载

👉 [点击下载奶蛙压缩包](https://github.com/YixiTang/Naiwa_codex_pet/raw/refs/heads/main/naiwa-portable.zip)

下载后解压，详细安装说明见压缩包内的 `readme.txt`。

## Windows 安装方法

需要使用支持 Pets 和 sprite v2 的 Codex 桌面客户端。

1. 下载并解压压缩包。
2. 在文件资源管理器地址栏输入 `%USERPROFILE%\.codex\pets`，如果目录不存在则创建。
3. 将解压得到的整个 `naiwa` 文件夹复制到该目录。
4. 确认目录结构如下：

   ```text
   .codex/
   └─ pets/
      └─ naiwa/
         ├─ pet.json
         └─ spritesheet.png
   ```

5. 重启 Codex，在 Settings → Pets 中选择“奶蛙”。
6. 使用 `/pet` 或 Show pet 显示桌宠。

如果自行设置过 `CODEX_HOME`，请使用该目录下的 `pets` 文件夹。其他路径说明见 `readme.txt`。

## 动作与触发方式

| 动作 | 触发方式 |
|---|---|
| 轻微呼吸、眨眼 | 待机 |
| 左推掌 | 向左拖动 |
| 右推掌 | 向右拖动 |
| 捧腹大笑，电脑自然掉落 | 鼠标悬停 |
| 左右摆动 | 首次唤醒的欢迎阶段 |
| 摸头 | 任务失败或出现错误 |
| 长出翅膀、双手合十 | 等待用户回答或确认 |
| 手持电脑操作 | 正在工作 |
| 双手点赞 | 任务完成，结果待查看 |

首次欢迎不一定在每次打开时播放；具体触发行为由客户端控制。

## 文件内容

- `readme.txt`：完整安装与使用说明。
- `naiwa/pet.json`：桌宠配置。
- `naiwa/spritesheet.png`：动画图集。

请保持配置文件与动画图集的文件名和相对位置不变。
