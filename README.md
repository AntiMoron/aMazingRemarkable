# aMazingRemarkable
=================== 前言========================

嚯！又是一个巨坑。我承认，aMazing其实很烂。
烂到我自己都写不下去了。排除工作加班原因每周末我都全心投入到LOL事业中。

That is not good for me.

现在要重构aMazing.
重构必定有更好的东西，需要这样一次又一次地写才能让其更好。

===================分割线=======================

重做aMazing。实现几个新目标

0. 严格实行统一的编码规则
1. 认真做宏观的规划，让内容更加合理
2. 全面基于stl，让我变屌。
3. 严格规定文件格式，让aMazing真正框架化
4. 完成各种文件格式的解析 --> Json
5. 多用TMP （权当练习）
6. 多用模式，减少硬编码
7. 认真地维护语义，不搞容易给自己搞sb的设定。

===================分割线=======================

# 目标
0. 基于消息的回调处理系统
  0. 明确支持单一Device
  1. 支持多DeviceContext
  2. 支持Win消息处理 (更抽象，方便底层实现替换）
  3. 支持消息回调
1. Language系统
  0. DSL语言支配每一pass的Shader绑定和使用流程
    0. Lex约定
    1. Syntax约定
    2. ABI约定
2. 渲染系统
  0. 3D渲染
    0. Mesh
    1. 基础图元
    2. 纹理
    3. 骨骼动画
    4. 矢量动画
    5. PRS
  1. 2D渲染
    0. 二值化
    1. 文字系统 
    2. 图片
    3. 透明度维护
3. 数据结构
  0. 方便适配顶点的OCT 
4. 声音系统
  0. XAUDIO
5. GUI系统
  0. 按钮
  1. IME输入
  2. Vedio.
6. 特效系统
  0. 3D渲染
    0. 雾
    1. 软阴影
    2. 金属光泽
    3. 反射
    4. 透明
    5. 玻璃
    6. 冰块
    7. 水
    8. 阳光
    9. SSAO
    10. FXAA
    11. MSAA
  1. 2D渲染
    0. 三原色分离
    1. 波浪
    2. 噪点
    3. 翻转
    4. 图片重叠
    5. 灰度
    6. 饱和度
7. 通信系统
  0. UDP局域网通信
8. 版本维护系统
  0. 版本文件格式设计
