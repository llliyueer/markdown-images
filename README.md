
# StereoVision文档整理

标签（空格分隔）： 未分类

---
**重建步骤【4】**点云三角化及渲染： 
<span id="OnBnClickedTriangulationandrendering">OnBnClickedTriangulationandrendering：</span>
主代码：
```c++
for ( i = 0; i < 73 -2; i + = 2)
// @ 该match含有最后压进去的0视角，所以大小为=36*2+1
// @ i(0:70;2++)；总共循环36次
// - i/2（0:35)；代表各视角
{
    for(j = 0;j < 各视角的三维点个数；j++)
    {
        找到统一坐标系下的所有重建点的三维坐标范围
    }
    TriSubDiv（in:[1]当前视角下左图特征点的像素坐标，[2]当前视角的左图像，out:[3]?????）
}




```# markdown-images
the images in my markdown notes need a ID
