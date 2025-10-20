无论何时你想要创建新样式，都可以添加新的 CSS 类。 确保给该样式起一个合理的名称。

尝试确保你的样式可重复使用并且只包含你想要一起使用的属性。

![一只周围有白色边框的甲虫。 底部边框较大。](images/beetle-photo.png)

这个 `photo` 类创建了一种可以应用于图像的印刷照片风格。

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

/* 印刷照片风格 */

.photo {
  border: 1px solid #D0D0D0; /* 添加实线边框 */
  width: 14rem;
  height: 15rem;
  background: #ffffff;
  padding-top: 1rem;
  padding-left: 1rem;
  padding-right: 1rem;
  padding-bottom: 3rem;
  box-shadow: 8px 8px 10px 4px #888888; /* 右侧和底部阴影、模糊、扩散和颜色 */
  transform: rotate(3deg);
}

--- /code ---

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<section>
  <img class="photo" src="beetle.jpg">
</section>

--- /code ---


