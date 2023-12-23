### 学习目标
***
- 初步学习unity引擎
### 学习笔记
***
#### 基本组件
- Rigidbody 2D   
  物理刚体组件，使物体有物理运动。     
  参数：    
  - Body Type：   
    1.Dynamic:物理运动，使物体具有真实的运动效果。   
    2.Kinematic:自定义运动效果，不受自动刚体影响。   
    3.Static:静止。
  - Sleeping Mode:设置成Never Sleep!偶尔的睡眠会导致刚体失效。
  - Velocity:运动速度，设置物体运动。
- Collider 2D    
  碰撞体组件，设置碰撞范围。   
  参数：
  - IsTrigger:勾选后，仅作为触发器使用，没有物理碰撞效果。   
  - Offset和Size :碰撞范围和位置。   
  - Layer Overrides:设置包含图层和排除图层。包含或排除的图层将无法发生碰撞和触发及反馈。
- Sprite Renderer
  绘制图片组件。   
  参数：   
  - Material:设置材质，可以实现灯光效果，配合bloom可以实现调节物体光晕。  
  - Additional Settings:图层排序。  
      

 


