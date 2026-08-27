# 什么都没有发生 / Nothing Happened

> 一颗卵子的重量，三点五微克。五千万美元现金的重量，两点五吨。
> The weight of one egg: 3.5 micrograms. The weight of fifty million dollars in cash: 2.5 tons.

根据短篇小说《我的女友景甜》改编的沉浸式叙事游戏原型。人物已全部化名（苏夏、苏国庆、夏心爱），故事纯属虚构。
An immersive narrative game prototype adapted from a short story. All characters are fictionalized (Su Xia, Su Guoging, Xia Xin'ai). The story is purely fictional.

## 在线试玩 · Play Online

- GitHub Pages：<https://jounghu.github.io/SungeLife/>
- Gitee Pages：<https://jounghu.gitee.io/sunge-life/>

## 这是什么 · What This Is

- 极简黑底白字叙事游戏，完整复刻小说的剧情流程
- **零依赖、零外部资源**：单文件 HTML，所有图片由代码生成（Canvas / SVG），所有声音由 Web Audio 实时合成
- 亲手操作的关键时刻：磨指甲、贴胶带、**在 Claude Code 终端里输入指令**、最后那通电话的**十一秒静默**
- 四个结局，由整局的选择决定：钱 / 沉默 / 相信 / 说不

- A minimal black-and-white narrative game that fully follows the original story
- **Zero dependencies, zero external assets**: single-file HTML; all visuals generated in code (Canvas/SVG); all sound synthesized live with Web Audio
- Hands-on moments: nail filing, window taping, **typing commands into a Claude Code terminal**, and an **11-second silence** on the final call
- Four endings shaped by your choices across the whole run: Money / Silence / Trust / Saying No

## 操作方式 · Controls

- **点击 / 回车**：推进文字（打字中点一下 = 当前行打完；再点一下 = 下一行；全部读完再点一下 = 出现选项 / 进入下一场景）
  **Click / Enter**: advance text (one click finishes the current line; another reveals the next line; after the last line, one more click shows choices or moves on)
- **数字键 1–9**：选择对应选项 / **Keys 1–9**: choose an option
- 右上角：**全屏** / **声音** 开关 / Top-right: **fullscreen** / **sound** toggle
- 磨指甲小游戏：鼠标从左往右拖（空格键可代替）；贴胶带小游戏：点击六处漏光点
  Nail filing: drag left to right (or press Space). Window taping: click the six spots that let light in.

## 本地运行 · Run Locally

直接双击 `index.html`，或起一个本地服务器 / Double-click `index.html`, or run a local server:

```bash
python -m http.server 8000
```

然后访问 <http://localhost:8000> / Then visit <http://localhost:8000>.

## 目录结构 · Project Structure

```
index.html   Game (root copy, ready for GitHub / Gitee Pages deployment)
game/        Game source directory (with its own README and asset notes)
```

## 版权说明 · Notes

游戏内人物已全部化名；故事为虚构作品。如需公开发布，建议将蒙太奇、索尼娃贾尼等真实地名一并替换。
All characters are fictionalized and the story is fictional. Consider replacing real place names (Montage, Soneva Jani, etc.) before public deployment.
