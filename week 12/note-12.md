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
  - 动画制作
    1.将animation拖进animator，进行不同动画的切换
    2.Parameters:animator的变量，用与当作动画切换的条件
    3.Layers:不同动画图层，图层之间可以覆盖，也可以叠加。  
    4.Make Transition:动画之间的过渡线  
      - Has Exit Time:上一个动画的退出时间，满足条件才会进行动画切换  
      - Fixed Duration:动画叠加  
      - Conditions:设置条件变量，满足才进行动画切换  
      - Can Transition To Self:Any State中是否可以打断自身。(通过Any State进入的动画是否会同样被Any State打断)   
        Any State：在任何动画执行时，只要满足执行条件，便可以打断当前动画执行，进入目标动画。
      - 可以设置多个条件，同时满足后进行动画切换
  - 动画执行逻辑
    1.Add Behaviour:创建 
