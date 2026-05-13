---
# 整个演示文稿及第一张幻灯片的配置

addons:
  - slidev-addon-python-runner
  - slidev-addon-rabbit
rabbit:
  slideNum: true   # 在兔子图标旁显示当前/总幻灯片数

theme: bricks

# 幻灯片的一些信息（支持 markdown）
title: Python 系列教程
author: Kareim Tarek
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false

# 幻灯片过渡动画: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left

# 启用 MDC 语法: https://sli.dev/features/mdc
mdc: true

# 在代码块中显示行号
lineNumbers: True

# 控制幻灯片中的文本是否可选中
selectable: true
---

# Python 从入门到放弃

第一集

<div class="abs-br m-6 text-xl">
  <a href="https://www.youtube.com/@KareemKreates" target="_blank" class="slidev-icon-btn">
    <carbon:logo-youtube />
  </a>
  <a href="https://github.com/KareimGazer" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
    <a href="https://x.com/KareimGazer" target="_blank" class="slidev-icon-btn">
    <carbon:logo-x />
  </a>
</div>

<!--
每张幻灯片的最后一个注释块将被视为幻灯片备注。在演示者模式下，它将可见且可编辑。
-->

---
src: ./pages/toc.md
---

---
src: ./pages/why.md
---

---
src: ./pages/intro.md
---

---
src: ./pages/1.md
---

---
src: ./pages/2.md
---

---
src: ./pages/3.md
---

---
src: ./pages/4.md
---

---
src: ./pages/5.md
---

---
src: ./pages/6.md
---

---
src: ./pages/7.md
---

---
src: ./pages/8.md
---

---
src: ./pages/9.md
---

---
src: ./pages/10.md
---

---
layout: center
class: text-center
---

# 了解更多

[资料](https://sli.dev) · [GitHub](https://github.com/KareimGazer) · [YouTube](https://www.youtube.com/@KareemKreates)

<PoweredBySlidev mt-10 />
