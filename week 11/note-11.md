## 学习目标   
***   
- 学习图片的切割
- 学习动画的制作
## 学习笔记   
***       
- 图片的切割
  - Pixels Per Unit:决定图片大小  
  - Sprite Mode:切割类型，有单一和多个。
  - Filter Mode: 像素填充，一般不用。
  - Compression:图片压缩
  - Max Size:最大像素，与图片分辨率有关
  - Sprite Editor     
    图片切割工具，切割完记得点 Apply!    
    - Slice ->   
      1.Type:自动切割。按照数量比例切割。安装像素比例切割。    
      2.Pivot:Sprite的中心点，瓦片地图设置成Center!  
    - Sprite Editor ->   
      1.Custom Physics Shape:自定义物理碰撞形状。 
- 动画的制作
  - 动画帧制作
    1.创建animation动画文件
    2.直接拖入对应动画的Sprite   
    3.通过设置Samples 设置采样率   
    4.通过Add Property 添加动画播放时物体的一些改变(参数变量，组件激活状态)
    5.在每一帧动画上面可以添加事件，在物体上挂写好要执行的函数的脚本后可以直接调用
  
