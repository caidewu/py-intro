---
transition: slide-left
---

# 为什么选择 Python？

- 📝 **流行、易学** 的编程语言。
- 🛠 适合快速 **原型开发**
- 🧑‍💻 广泛应用于 **数据分析**、**机器学习** 和 **人工智能** 领域。

Python 拥有非常高效的数据处理库，包括我们将在本课程中熟悉的 `NumPy`、`Pandas`、`Matplotlib` 和 `SciPy` 等库。

[Python 官方文档！](https://docs.python.org/3/)

<div class="w-60 relative">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 2, rotate: -100 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-square.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute inset-0"
      src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg"
      alt=""
    />
  </div>

  <div
    class="text-5xl absolute top-14 left-40 text-[#f0ec07] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Python
  </div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!-- vue script setup 脚本可以直接在 markdown 中使用，且仅影响当前页面 -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>
