# 荣世法律科技 · 楼层信息大屏（前端骨架）

仅提供结构与占位，不实现业务功能。适配 6 层楼、支持后续与移动端互动。

## 开发

1. 安装依赖
```bash
npm i
```

2. 本地运行
```bash
npm run dev
```

## 结构

```
bigscreen/
  ├─ index.html
  ├─ src/
  │  ├─ App.tsx
  │  ├─ main.tsx
  │  ├─ styles/
  │  │  └─ index.css
  │  ├─ components/
  │  │  ├─ TopInfoBar.tsx
  │  │  ├─ LightPillar.tsx
  │  │  ├─ ElevatorSlider.tsx
  │  │  ├─ FloorPanel.tsx
  │  │  └─ AmbientFX.tsx
  │  ├─ types/
  │  │  └─ index.ts
  │  └─ config/
  │     └─ company.ts
  ├─ package.json
  ├─ tsconfig.json
  └─ vite.config.ts
```

## 后续工作
- 填充 `config/company.ts` 的每层设施、团队、业务的真实数据。
- 根据 `BIGSCREEN_UI.md` 补齐动画与交互逻辑。
- 接入移动端联动的 WebSocket 和 REST 数据。


