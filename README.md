# Qhyd 流量计算与喷雾仿真系统 (PWA 版)

集成以下三大模块：
1. **流量计算 (Qhyd)**：支持基准参数计算、Excel 客户表导入、单变量 Sweep 扫描、曲线族自动对比与多图合并导出。
2. **喷雾仿真（俯视）**：支持 A/B 双工况对比、2D 流体计算、实时贯距监测、帧回放及 PNG / MP4 视频导出。
3. **孔径 & 流量系数**：支持已知流量反算孔径 `D`、反算流量系数 `µ`、一维曲线对比与双参数 Map 热力图导出。

## GitHub Pages 部署步骤
1. 在 GitHub 新建一个仓库（Public 或 Private 均可，免费版建议 Public）。
2. 将压缩包内的所有文件（`index.html`、`manifest.json`、`sw.js`、`icons/` 文件夹、`.nojekyll`）上传至仓库根目录。
3. 进入仓库的 **Settings -> Pages**。
4. 在 **Build and deployment -> Source** 下选择 **Deploy from a branch**，分支选 `main`（文件夹选 `/ (root)`），点击 **Save**。
5. 等待 1~2 分钟，访问生成的 `https://<你的用户名>.github.io/<仓库名>/` 即可使用。
6. 在电脑 Chrome/Edge 地址栏右侧点击 **“安装应用”**，或在手机浏览器选择 **“添加到主屏幕”**，即可作为独立 App 离线运行。
