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
