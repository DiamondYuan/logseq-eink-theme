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
