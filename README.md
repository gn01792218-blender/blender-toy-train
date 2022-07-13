# blender-toy-train
## 建模步驟
### 1.導入參照圖、並管理collection
### 2.依照圖形建立基礎模型
### 3.設置模型的parent關係，並Z軸旋轉車廂到想要的位置
#### 每一台車子都parent到其前方的link上
### 4.apply scale
### 5.套用修改器
#### (1)Bevel修改器+shade smooth : offset 0.01m Angle 30<br>
        完成設置後，A全選，ctrl+L 設置修改器modifilers到所有模型上。<br>
        最後右鍵shade smooth。
### 6.攝影機設置
#### (1)將攝影機擺放到當前視角 : ctrl + alt +0 
#### (2)鎖定攝影鏡頭 : 開啟N面板-->View-->Lock camera to view 。
### 7.顏色 
#### (1)顯現物體顏色 : viewport shading-->color-->object
#### (2)修改顏色 : object property-->viewport display-->color
#### (3)複製顏色到其他物件上 : hover在color bar上 ctrl+c複製；hover另個物件的Color bar ctrl+v貼上
### 8.Render property - workbench
#### (1)勾選Cavity
#### (2)勾選Depth of Field
#### (3)調整shadow強度、點選旁邊的設置紐，可以調整陰影的方向
#### (4)在Lighting下的Studio，點選圓球，可以選擇studio的濾鏡模式唷
### 9.設置camara景深(Depth of field)
#### 要設置攝影機的景深，必須要先勾選Render property中的Depth of Field
#### (1)點選相機，來到Object data property，設置Focus on object選擇焦點物件
#### (2)設置F-Stop，來調整光圈
### 10.渲染圖片 - F12 
#### 圖片Render選擇32Samples

