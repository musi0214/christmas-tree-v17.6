# Christmas Tree · v17.6

一个纯静态的交互式圣诞树页面：旋转的螺旋彩灯圣诞树、飘雪、星芒与八音盒版《铃儿响叮当》。

## 预览

打开 `index.html` 或访问 GitHub Pages 部署地址即可。

## 特性

- 单文件、零依赖，离线可用
- Canvas 粒子渲染，适配手机与桌面（含 DPR 高清与安全区）
- 顶部按钮：暂停/继续动画、开/关音乐（Web Audio 合成，无需音频文件）
- 尊重系统「减少动态效果」设置

## 本地运行

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

仓库 Settings → Pages → Source 选择 `main` 分支根目录即可。

## License

MIT
