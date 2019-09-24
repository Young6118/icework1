# ice-scaffold-lite

## 使用

- 启动调试服务: `npm start`
- 构建 dist: `npm run build`

## 效果图

![screenshot](https://img.alicdn.com/tfs/TB1CjPVw4naK1RjSZFBXXcW7VXa-2872-1580.png)

## 发布git pages

* `npm install gh-pages --save-dev`

* package.json 修改

> 增加 homepage 配置（react）

```
"homepage": "https://youngchou1997.github.io/icework1",
```

> scripts 中增加

```
"pregh": "ice-scripts build",
"gh": "gh-pages -d build"
```

* `npm run gh`