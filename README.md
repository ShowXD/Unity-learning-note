# Unity-learning-note

## Scene
### 異步載入
<br>
與其他載入不一樣的是他不會100%將效能都花費在載入場景中，藉此來顯示loading畫面
<br>
- 他可以當成物件，會回傳現在的載入進度，以0~0.9分類

```
SceneManager.LoadSceneAsync()
```
