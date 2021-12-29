---
title: "Testing 1"
date: 2021-12-29T15:58:27+08:00
categories: ["x"]
tags: ["x", "x"]
toc: false
draft: true
license: '<a rel="license external nofollow noopener noreffer" href="https://creativecommons.org/licenses/by-nc-nd/4.0/" target="_blank">CC BY-NC-ND 4.0</a>'
---
Start here to write...

这篇文章的 `md` 源文件中 **包含**  `Pjax` 函数，出现了空的 `<blockquote></blockquote>`：

<script>
window.TWIKOO_MAGIC_PATH="/testing-1/"
document.addEventListener('pjax:send', function () {
    window.TWIKOO_MAGIC_PATH=""
});
</script>