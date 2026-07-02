# 国服打法适配版

目前支持P2、P3一运、P3二运(D-TN-死宣/TDN优先级/TDN双线)、P4(支持人前人后、盗火固定、石化场中)、P5（新增NOCCHH分散站位、修改黄紫圈刷新规律、新增黄紫圈只以当前玩家为目标）

P2打法预设：

1、原盗火+闲人固定(左钢右扇+闲固+非对射)

2、22混合原版，(永远左扇右钢+对射)

3、22混合+闲人固定(左扇右钢+闲固+对射)

4、MMW解法3盗火闲人固定(左扇右钢+闲固+非对射)

5、盗火2队（左扇右钢+闲固+对射）

同点名换位都是相对左右

# Waju-Sims

Download links:

DMU: https://github.com/WCGH/Waju-Sims/releases/tag/dmu-0.1.x

FRU: https://github.com/WCGH/FRU-Sim/releases/tag/v1.8

DSR: https://github.com/WCGH/Dragonsong-Sim/releases/tag/v1.1


If you have any questions or feedback let me know on discord. https://discord.gg/P9adFHADrX

## Note on renderer compatability issues and running on Linux:

If the sim fails to launch or consistently crashes, it is usually a rendering issue. The sim by default runs on DX12 but you can run it on Vulkan through cmd line arguments.

For Windows users: Shift+Right click anywhere inside the folder containing dmu-sim.exe > Open PowerShell window here > Enter `./dmu-sim.exe --rendering-driver vulkan`

The same arguments should also work for Linux users running it through Wine.

Alternative for Linux Users: you can download the Linux version of the Godot engine (any 4.7 version should work). Extract the `godot_..._linux.x86_64` file and rename it to `dmu-sim` and run it in the dmu-sim folder.

If you're on a laptop with integrated GPU and neither DX12 or Vulkan works, you can also try replacing `vulkan` with `opengl3`, though you will see a big drop in performance.


If you have any questions or feedback let me know on discord.
