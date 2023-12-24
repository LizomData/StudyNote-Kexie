## 学习目标   
***   
- URP灯光学习
- 学习事件！！！
## 学习笔记   
***       
- 创建 2D URP渲染管线
- 开启相机后处理(图像的光晕，绽放...)   
- Light 2D     
  1.Sprite Light2D:图片灯光    
  2.Spot Light2D:  
   - Intensity:灯光亮度    
   - Inner:灯光内圆    
   - Outer：灯光外圆    
   - Falloff Strength:灯光覆盖度    
   - Shadows:灯光阴影   
- 事件：
  - Event:  
    - AddListener:事件添加,AddListener(() => {});   
    - RemoveAllListeners：事件去除
  - Action:
    - myAction += ...
    - myAction -= ...
    - myAction += () => {};
  - 利用scriptableobject实现全场景广播和监听(发布模式不可用！)
    - 创建public action变量
    - 在不同脚本中Invoke 或 添加事件
  - DoTween回调函数
    - OnComplete（TweenCallback回调）
    - OnStepComplete（TweenCallback回调）
    - OnKill（TweenCallback回调）
    - OnPlay（TweenCallback回调）
    - OnPause（TweenCallback回调）
    - OnStart（TweenCallback回调）
    - OnUpdate（TweenCallback回调）
    - OnRewind（TweenCallback回调）

