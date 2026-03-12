# 设计规范

## 美化原则

- 只改样式，不动业务逻辑
- 所有颜色通过 CSS 变量统一管理

## 色彩系统

- 主色：#1e40af（深蓝）
- 高质：#059669（翠绿）
- 中质：#d97706（琥珀橙）
- 低质：#dc2626（红）
- 背景：#f8fafc
- 卡片：#ffffff，border: 1px solid rgba(0,0,0,0.06)

## 阴影

- 卡片：0 1px 3px rgba(0,0,0,0.06), 0 4px 16px rgba(0,0,0,0.04)

## 动效

- 页面加载用 staggered fadeUp，时长 0.4s
- hover 过渡统一 0.15s ease

## 字体规范

- 大数字：font-weight 800，letter-spacing -0.02em
- 说明文字：opacity 0.6
