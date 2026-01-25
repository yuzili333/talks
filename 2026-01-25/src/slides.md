---
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
mdc: true
layout: center
glowSeed: 4
lang: en
title: Scratchjr Push Box
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

<p text-6xl>Push Box</p>

<div abs-br mx-10 my-11 flex="~ gap-2 items-center" text-left op75>
  <img src="/anthropic-logo.svg" h-8 alt="CibConf">
  <div>
    <div text-lg>Scratchjr</div>
    <div text-xs opacity-75>Jan. 18th, 2026</div>
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

今天我们的主题是一个叫做推箱子的游戏，大家可以叫他做Push-Box，我们需要移动箱子的位置来达到目的，不论是获取财宝还是抵达目的地。

-->

---
class: p0
glow: bottom
---

<div class="grid grid-cols-[3fr_4fr] gap-4 h-full">

  <div ma flex="~ col gap-2 items-center">
    <p text-4xl>Scratchjr Animation</p>
    <div text-orange text-sm bg-orange:10 px2 rounded>Push Box</div>
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

**老师**：“小朋友们好！今天我们要做一个关于推箱子的游戏。”

**互动**：来我们玩一个关于推箱子的游戏，请各位小朋友关注该游戏中有哪些角色、动作以及场景。

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
<div flex="~ items-center" w-140 p-8><img src="/push-box.png" w-120 /></div>
<div flex="~ col gap-2 justify-center">

# Push Box

Play Push Box Game

</div>
</div>

<!--

#### 请小朋友推箱子游戏中有哪些角色

- 有哪些角色参与了这个游戏
- 这些角色分别有什么动作
- 推箱子过程会遇到哪些障碍物
- 需要完成做什么操作才能顺利帮助小推箱子到达目的地

#### 介绍本节课要完成的动作

- 1、绘制一个小朋友喜欢的推箱子背景，并添加一个推箱子的角色。
- 2、设计推箱子的路线，根据网格图计算需要移动的方向和距离。
- 3、为推箱子角色编写程序，使其能够通过点击屏幕上的按钮来移动推箱子。

**难点** 如何实现推箱子角色的移动路线，根据箱子、目的地和当前角色位置，计算出需要移动的方向和距离。

**加分项**

- 评选最美设计背景、推箱子绘制
- 录制推箱子碰到障碍物的声音的音效、开心的音效、哭泣的音效等

-->

---
layout: intro
class: text-center pb-5
glowX: 50
glowY: 120
---

<h1 font-serif important-text-5em>Thank You</h1>

Slides available at [yzl.me](https://github.com/POfeiY)
