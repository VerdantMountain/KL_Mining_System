<p align="center">
  <img src="https://github.com/qingshan2048/img/blob/main/ethereum.png" width="260">
</p>
<p align="center">
  <img src='https://img.shields.io/github/license/matevip/matecloud' alt='License'/>
  <img src="https://img.shields.io/github/stars/matevip/artemis" alt="Stars"/>
  <img src="https://img.shields.io/badge/VUE-3.2.2-green" alt="VUE"/>
  <img src="https://img.shields.io/badge/VueRouter-4.0.11-blue" alt="vue-router4"/>
  <img src="https://img.shields.io/badge/Vite-2.5.0-brightgreen" alt="Vite"/>
</p>


# 矿龙 `最好用的智能挖矿引擎`

## 💡 简介

- 青山软件，必是精品，矿龙智能挖矿引擎，最好用的智能挖矿引擎，网吧，游戏工作室挖矿最好用的工具

## 🔥 优势
- 目前显卡价格水涨船高，挖矿程序可以有效收回显卡的溢价成本，甚至盈余

## 💥 特性

- **图形界面**：操作界面干净整洁，简易易懂，方便操作
- **矿龙算法**：采用底层纯C编写，运行稳定流畅不卡顿
- **智能优化**：软件会根据PC端的实际情况进行算法优化以及强度调整，最大限度的保证了机器的无影响运行
- **挖矿内核**：内置性能优良的挖矿内核，保证物理机算力的最大利用率
- **游戏避让**：可以智能躲避大型游戏，优先保证客户体验
- **软件更新**：软件保持高频率的更新，最大限度的保证与政策和性能的高度兼容
- **加密数据**：矿龙内的数据全部采用了数据加密处理，不会再数据传输中被任何通信商侦测

## 🍯 软件展示
![Image text](https://github.com/qingshan2048/img/blob/main/a.jpg)

## 📝 文件说明

- `KUANGLONG vx.xx.exe` - 矿龙挖矿引擎生成器，主程序
- `GPU-Z.2.43.0.exe` - 最新的GPU查看工具，方便查看GPU的负载工作状态
- `显卡性能表.JPG` - 为机器配置挖矿程序的显卡算力参考图
- `README.md` - 程序说明文件

## 🌐 推荐矿池

- [鱼池](http://f2pool.com/) - 鱼池，世界上最大的矿池之一
- [BTC](http://btc.com/) - BTC，口碑不错，好用

## 🔨 安装使用

- 运行环境

```bash
Windows 7/8/10/11
```

- 软件使用

```bash
双击运行软件，配置参数，选择输出目录，生成引擎
```

- 挖矿引擎使用方法

```bash
将生成的挖矿引擎存放于c盘目录下，设置开机启动即可
```

- 数据上线

```bash
稍等一段时间，即可在矿池后台看到数据
```

## 🌭 参数配置
|  矿池配置   |   格式  |   说明   |
|---  |--- | --- |
|  TCP协议   |  eth.f2pool.com:6688   |  直接填写（ip:端口）则默认走tcp协议，备用矿池地址可留空   |
|  TCP协议   |  stratum+tcp://eth.f2pool.com:6688   |  完整格式，备用矿池地址可留空   |
|  SSL加密   |  stratum+ssl://eth.f2pool.com:6688   |  完整格式，备用矿池地址可留空   |

## 🔧 相关工具
### 👉 翻墙工具：https://i.sw19.icu/kUeN

VPN名称 | 速度| 注册地址
---|---|---
速蛙云 | 极快| https://i.sw19.icu/kUeN

很多矿池主页大陆已经无法正常访问，需要借助VPN工具

## 🔨 更新日志

- 参考 [vue](https://github.com/vuejs/vue/blob/dev/.github/COMMIT_CONVENTION.md) 规范 ([Angular](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular))

- `2022-01-21` - 1.12版本
软件将支持数据加密传输，保证挖矿数据的安全
做了软件的自身加密，对关键数据全部与功能绑定，防止被他人进行代码的恶意篡改
取消了单线程轮滚式执行模式，采用了更先进的多路定时器自动触发执行，同时缓解了定时机制在windows系统中优先级低下的天然缺陷
采用多线程并行处理内核调控机制，增加了程序的流畅性同时避免了进程阻塞的情况
重新设计了程序的账户切换时序和逻辑，程序运行更缜密
- `2022-01-17` - 1.10版本
同时改进了程序的定时系统，规避了旧版本程序自我卡死的几率，
在生成界面新增了官网网址，可以方便更新到最新版本
- `2022-01-15` - 1.08版本
程序名字重新命名为矿龙网吧挖矿引擎，做出图形界面，可以用来配置生成器
取消了GPU防中断系统，实测此功能效率并不明显，
增加了程序自动释放的功能，取消了windows自带的iexpress打包机制，
将上机挖矿，待机挖矿，躲避游戏挖矿合并为统一进程集中调度
- `2021-12-25` - 1.06版本
对挖矿内核的本地访问端口进行了不规则端口设置，使程序不暴漏自己的挖矿特征
将风扇调节模式设置为自动调节
引入了全新的矿工警报系统，当发现有某游戏程序在进行或者远端服务器发出指令后，可以进行挖矿程序的停止和清除
该版本屏蔽了以下游戏，
穿越火线 crossfire，
绝地求生 TslGame，
反恐精英 csgo，
守望先锋 Overwatch，
反恐精英OL cstrike-online，
赛博朋克2077 Cyberpunk2077
- `2021-12-22` - 1.04版本
对电脑的风扇转速进行了控制和调节，更好的散热处理，有利于缓解卡顿现象，
重新设定了挖矿内核的本地访问端口，使程序不暴漏自己的挖矿特征，
挖矿程序自行设置自己为系统隐藏文件，提高了程序的隐蔽性，对试图删除自己的程序提出了更高的权限要求，
为挖矿程序增加了GPU防中断模式，当GPU再对游戏程序进行运算时，挖矿程序则不进行中断操作，保证游戏体验，
新增加了10个挖矿强度的版本，0.1到1.0为分别为10%到100%挖矿强度，
升级了网吧卡顿解决程序v1.04，兼容历史所有版本，一键清除所有挖矿程序
- `2021-12-20` - 1.02版本
采用了新的命名规则如QSRM(青山如梦)加上版本号，QSRM_1.02，方便后续版本升级进行挖矿效率的对比，
采用了全新的内核，硬件识别更准确更省时，挖矿效率更高，平均可提高1.5%的挖矿收益，
降低了挖矿账户的切换频率，可以更好减少检测硬件以及软件启动的时间成本，提升挖矿效益，
增加了挖矿程序的备用服务器，当挖矿程序无法进行联网的时候会启用内置的备用服务器进行连接，
新增加了3个挖矿强度的版本，0.4为40%挖矿强度，0.7为70%挖矿强度，1.0为100%挖矿强度，
测试设备用3dmark11跑分，显卡分数会随着挖矿强度的降低而升高，游戏体验有所增加

## 🚀 浏览器支持

本地开发推荐使用`Chrome 80+` 浏览器

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| :-: | :-: | :-: | :-: | :-: |
| not support | last 2 versions | last 2 versions | last 2 versions | last 2 versions |

## ✨ 特别鸣谢
特别感谢以下对本软件的发展和发展做出过帮助的人！
- SZDB: 本软件的第一个忠实用户
- SZDB: 本软件的第一个忠实用户

## 🐛 联系作者 🚑🎨
如有其他需求或者业务也可以通过以下方式联系作者

<img src="https://github.com/qingshan2048/img/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20220117145755.jpg" width="260">
