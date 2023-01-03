## APK下载链接：https://pan.baidu.com/s/19pEU76iJUp2cNHgRjF0ENw?pwd=ABCD 
## 以下为一加8手机运行时帧率
![yanshi](https://user-images.githubusercontent.com/49065462/210364051-238ce39a-4066-4fb7-a9dc-75f1b66cbd1f.jpg)
## 优化措施
- LOD可见距离设置
- 碰撞体简化（box代替mesh）
- 远景烘焙成天空盒
- 贴图资源格式，大小调整
- 场景物体细分（室内，室外，远景，近景等），物体区域加载（待进入对于的触发区域，才会触发加载逻辑，用于室内物体）
- 遮挡数据烘焙，减少摄像机过度绘制
- 后处理优化（主要对Bloom进行优化，降低采样次数，降低采样分辨率）
- 调整草，灌木丛，树木shader（将原本共用同一个shader逻辑抽离出来，细分为3个shader，只对自身表现做处理）
- Unity地形网格转换为相应的 MxN块 Mesh网格
  - 的
