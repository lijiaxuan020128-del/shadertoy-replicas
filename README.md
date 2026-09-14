# Shadertoy 本地复刻

用 WebGl2 在本地复刻的两个 Shadertoy 经典着色器，均为单文件页面（着色器内嵌），双击 `index.html` 即可运行，无需服务器。每个项目附带参数调节面板（滑杆实时生效，默认值等于原作效果）。

## 在线预览（GitHub Pages）

- 首页：<https://lijiaxuan020128-del.github.io/shadertoy-replicas/>
- [Creation](https://lijiaxuan020128-del.github.io/shadertoy-replicas/creation/)（在线版不含背景音乐，音乐仅本地提供）
- [Octagrams](https://lijiaxuan020128-del.github.io/shadertoy-replicas/octagrams/)


## 项目

### [creation/](creation/) — Creation by Silexars

- 原作：<https://www.shadertoy.com/view/XsXXDn>
- 作者：Silexars（Danilo Guanabara），DemoJS 2011 亚军，据称是首个 1kB WebGL intro
- 本地增强：参数滑杆（色散强度、波纹频率/流速、扭曲幅度、网格密度、辉光亮度、色相旋转、画面缩放）、鼠标悬停改变放射中心、背景音乐循环（音乐文件不入仓库）

### [octagrams/](octagrams/) — Octagrams

- 原作：<https://www.shadertoy.com/view/tlVGDt>
- 作者：whisky_shusuky，体积光线步进的八角星万花筒
- 本地增强：参数滑杆（相机速度、摇摆、辉光、迭代步数等）

## 使用

| 操作 | 效果 |
|---|---|
| 双击 index.html | 直接运行 |
| 鼠标悬停（creation） | 改变放射中心 |
| 点击画面 / 空格 | 暂停或继续 |
| ⚙ 参数按钮 | 展开/收起调节面板 |

## 许可与署名

两个着色器源码均保持原样或仅做参数化改写，遵循原作者在 Shadertoy 上的 **CC BY-NC-SA 3.0** 授权：署名-非商业性使用-相同方式共享。原作者信息已保留在各页面文件头部。音频文件（`.mp3`）因版权原因不纳入版本管理。
