# 鸣潮配置

> ## [可选] 部分配置依赖一个模组: [releases](https://github.com/AlteriaX/WuWa-Configs/releases)   
> ! 此模组直接为游戏添加了新代码，可能有封号风险，可以不装

### 覆盖文件:

- ``Scalability.ini`` 
  用来关闭一些后处理例如:
  > 色差, 景深, 胶片颗粒, 暗角  

  关闭这些效果可以显著提升性能，尤其适合低性能硬件或追求画质干净的玩家。


- ``DeviceProfiles.ini``   
   解决某些 **核显独显** 同时启用时在材质显示上的低质量问题。-**[图片](https://i.postimg.cc/W1jgWC4s/igpu.png)**
   > 某些材质（例如三花项链、金曦服饰上的铜鳞片、Black Shores 水波效果 等）可能显示模糊或质量较低。

- ``Engine.ini`` (从下面选一个配置)

---
覆盖文件的文件夹在：
> ..Wuthering Waves\Wuthering Waves Game\Client\Saved\Config\WindowsNoEditor

| 配置 | NVIDIA                                                                            | AMD                                                                   | Intel                |
|--------|-----------------------------------------------------------------------------------|-----------------------------------------------------------------------|----------------------|
| 1      | RTX 4090, 4080, 4070, 3090, 3080 Ti, 3080, 3070 Ti                                | RX 7900 XTX/XT/GRE, 7800 XT, 7700 XT, 6950 XT, 6900 XT, 6800 XT, 6800 |                      |
| 2      | RTX 4060 Ti, 4060, 3070, 3060 Ti, 3060, 3050, 2080, 2070, 2060, GTX 1080 Ti, 1080 | RX 7600 XT, 6700 XT, 6700, 6650 XT, 6600 XT, 6600, 5700 XT, 5700      | A770, A750, A580     |
| 3      | GTX 1660 Ti, 1660 SUPER, 1660, 1650 SUPER, 1070, 1060 6GB                         | RX 6500 XT, 5600 XT, 5500 XT, 590, 580                                |                      |
| 4      | RTX 2050, GTX 1650, 1050 Ti, 1050                                                 | RX 6400, 580 2048SP, 570, 560, 780M, 680M                             | A380, A310, Arc iGPU |
| 5      | GT 1030, MX350/250/150                                                            | RX 550, Vega iGPU                                                     | Iris Xe              |

引用: [UE4.27 Commands](https://framedsc.com/GeneralGuides/ue4_commands.htm), [UE4 Documentation](https://docs.unrealengine.com/4.27/en-US/), UE Forum
  
   
---
原项目 https://github.com/AlteriaX/WuWa-Configs

[<img src="https://i.imgur.com/fxmOE8N.png">](https://ko-fi.com/alteria/)