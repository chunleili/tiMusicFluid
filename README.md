# tiMusicFluid
taichi Hackathon 参赛

目前只是在筹划阶段

# 项目介绍

借助第三方商软：Houdini

随着音乐起舞的流体仿真模拟。

从python / Houdini 预处理音频文件，得到数据后送入taichi所写的物理仿真程序（暂定SPH）。根据音频数据改变施加到每个粒子上面的受力，从而让流体随着音乐“起舞”。最后送入Houdini渲染结果。

灵感来源是这个MV：https://www.youtube.com/watch?v=Q3oItpVa9fs
