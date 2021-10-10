## 改动

### 滚动条

1. 添加左边框 (border-left)

```css
html ::-webkit-scrollbar {
  border-left: 1px solid black;
}
```

2. 修改滑块背景色

```css
html ::-webkit-scrollbar-thumb {
  background-color: black !important;
}
```

### 侧边栏

1. 添加左边框 (border-left)

```css
#right-sidebar-container {
  border-left: 1px solid black !important;
}
```

2. 移除块的阴影、增加分割线

```css
.sidebar-item {
  box-shadow: none;
  border-bottom: 1px solid black !important;
}
```

### 编辑器

1. 辅助线颜色

```css
.white-theme,
html[data-theme="light"] {
  --ls-guideline-color: rgba(00, 00, 00, 0.7);
}
```

2. 引用次数

```css
.white-theme,
html[data-theme="light"] {
  --ls-link-text-color: rgba(00, 00, 00, 0.7);
}
.open-block-ref-link {
  opacity: 1;
  border: 1px solid var(--ls-link-text-color);
}
```

### 悬浮框

```css
.tippy-popper {
  border: 1px solid var(--ls-link-text-color);
}
```

### 命令面板

```css
.cp__palette-main .chosen {
  background-color: black !important;
}
.cp__palette-main .chosen code:first-child {
  color: white;
  opacity: 1;
}
.ui__modal-panel {
  border: 1px solid black !important;
}

.cp__palette-main code:nth-child(2) {
  background: rgba(00, 00, 00, 0.3);
  color: white;
}

.cp__palette-main .chosen code:nth-child(2) {
  background: white;
  color: black;
}
```
