---
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
mdc: true
layout: center
glowSeed: 4
lang: en
title: Scratchjr Pac-Man
---

![](/y-logo-animated.svg){.w-30.mt--10.mb-5}

---
layout: intro
class: pl-25
glowSeed: 14
---

<h1 font-serif>Zili Yu</h1>

<div class="[&>*]:important-leading-10 opacity-80">

Core team member of {XzhLabs}<br>
Creator of {xzh-jssdk} {invoker} {cli-tools}<br>
Maintainer of {CloudAlbum} {FormCreater} {Schedule}<br>
Based in ChengDu

</div>

<div my-10 w-min flex="~ gap-1" items-center justify-center>
  <div i-ri-user-3-line op50 ma text-xl />
  <div><a href="https://github.com/POfeiY" target="_blank" class="border-none! font-300">POfeiY.me</a></div>
  <div i-ri-github-line op50 ma text-xl ml4/>
  <div><a href="https://github.com/POfeiY" target="_blank" class="border-none! font-300">POfeiY</a></div>
  <div i-ri-twitter-x-line op50 ma text-xl ml4/>
  <div><a href="https://github.com/POfeiY" target="_blank" class="border-none! font-300">POfeiY</a></div>
</div>

<img src="https://avatars.githubusercontent.com/u/18592121?v=4" rounded-full w-35 abs-tr mt-32 mr-30 />

<!--
...

For today's topic, let's get straight to the point. Let's talk about...
-->

---
layout: center
glow: bottom
class: text-center
---

<p text-6xl>Pac-Man</p>

<div abs-br mx-10 my-11 flex="~ gap-2 items-center" text-left op75>
  <img src="/anthropic-logo.svg" h-8 alt="CibConf">
  <div>
    <div text-lg>Scratchjr</div>
    <div text-xs opacity-75>Jan. 11th, 2026</div>
  </div>
</div>

<!--
**(讲者台词)**

今天由Tony老师为大家带来Scratchjr的课程内容

课程目标：

1.  **知识目标**：
    *   复习并熟练使用移动、外观、声音等基础模块。
    *   学习并掌握“发送消息”和“接收消息”模块，理解其在角色互动中的作用。
    *   学习如何添加和切换不同的背景。
2.  **能力目标**：
    *   能够独立完成一个包含多个角色和场景的动画故事。
    *   提升逻辑思维能力，理解“事件-响应”的编程模式。
    *   激发创意，鼓励学生设计自己的故事结尾。
3.  **情感目标**：
    *   在充满乐趣的游戏故事情景中学习，提升对编程的兴趣。
    *   通过合作与分享，体验创作的成就感。

今天我们的主题是一个叫做吃豆人的游戏，大家可以叫他做豆豆人，他最喜欢的活动就是吃豆豆啦。

-->

---
class: p0
glow: bottom
---

<div class="grid grid-cols-[3fr_4fr] gap-4 h-full">

  <div ma flex="~ col gap-2 items-center">
    <p text-4xl>Scratchjr Animation</p>
    <div text-orange text-sm bg-orange:10 px2 rounded>Pac-Man</div>
  </div>

  <div border="l main" h-full py10 flex="~ col gap-6 justify-center">
    <div flex="~ gap-2" relative v-click>
      <div i-material-symbols:check-circle text-green text-3xl ml--4.5 flex-none />
      <div flex="~ col gap-1">
        <div text-xl>Introduce</div>
        <div op65 text-sm>
          introduce lesson topic
        </div>
      </div>
    </div>
    <div flex="~ gap-2" relative v-click>
      <div i-material-symbols:check-circle text-green text-3xl ml--4.5 flex-none />
      <div flex="~ col gap-1">
        <div text-xl>Gaming</div>
        <div op65 text-sm>
          just play a game
        </div>
      </div>
    </div>
    <div flex="~ gap-2" relative v-click>
      <div i-material-symbols:build-circle text-orange text-3xl ml--4.5 flex-none />
      <div flex="~ col gap-1">
        <div text-xl>Learning</div>
        <div op65 text-sm>
          Course content.
        </div>
      </div>
    </div>
    <div flex="~ gap-2" relative v-click>
      <div i-material-symbols:build-circle text-orange text-3xl ml--4.5 flex-none />
      <div flex="~ col gap-1">
        <div text-xl>Just do it</div>
        <div op65 text-sm>
          Hands-on practice self
        </div>
      </div>
    </div>
    <div flex="~ gap-2" relative v-click>
      <div i-material-symbols:lightbulb-circle text-gray text-3xl ml--4.5 flex-none />
      <div flex="~ col gap-1">
        <div text-xl>Summarize</div>
        <div op65 text-sm>
          Summary presentation
        </div>
      </div>
    </div>
  </div>
</div>

<!--

**老师**：“小朋友们好！今天我们要做一个关于吃豆人游戏的动画效果。吃豆人最喜欢吃豆豆了，我们要帮他设计一个有趣的游戏故事！”

**互动**：来我们看关于吃豆人的一段视频，请各位小朋友关注该游戏中有哪些角色以及场景。

主要有以下几个内容

[click] 介绍课程

And then [click] 体验游戏过程

[click] 课程主要内容

[click] 动手实践

[click] And finally, 思考总结，回顾学习的内容

-->

---
class: important-p0
---

<div flex="~ gap-2 items-center" h-full>
<div flex="~ items-center" w-140 p-8><img src="/pac-man-new.png" w-120 /></div>
<div flex="~ col gap-2 justify-center">

# Pac-Man

PAC-MAN is a cultural icon

</div>
</div>

<!--

#### 请小朋友回顾吃豆人游戏中有哪些角色

- 吃豆人（豆豆）一直在做什么
- 吃豆豆过程会遇到哪些苦难
- 需要完成做什么操作才能顺利帮助豆豆顺利吃完全部的豆豆

#### 介绍本节课要完成的动作

- 1、绘制一个小朋友喜欢的背景，背景颜色可以自行选择，并添加一个吃豆人的角色。
- 2、添加多个豆豆角色，分别放置在不同的位置。
- 3、为吃豆人角色编写程序，使其能够通过点击屏幕上的箭头按钮来移动。
- 4、为每个豆豆角色编写程序，当吃豆人碰到豆豆时，豆豆会消失并播放一个吃豆的声音。
- 5、当所有豆豆都被吃掉后，显示成功结算画面（豆豆开心的跳起来舞动）；如果游戏中吃豆人被怪兽碰到，则显示失败画面（吃豆人伤心地坐下哭泣）。
- 6、录制一段吃豆豆时的声音效果，录制一段豆豆被怪兽阻止的效果
- 7、绘制吃豆人方向控制的按钮（上、下、左、右）

**难点** 如何实现时方向变换，循环移动，重复动作设计、以及快速复制豆豆角色，吃完全部豆豆后的判断等。

**加分项**

- 评选最美设计背景
- 录制吃豆人吃豆豆的音效、开心的音效、哭泣的音效等

-->

---
layout: intro
class: text-center pb-5
glowX: 50
glowY: 120
---

<h1 font-serif important-text-5em>Thank You</h1>

Slides available at [yzl.me](https://github.com/POfeiY)
