# 
<h1> Fall-Detect-alphapose-yolo-stgcn </h1>

![sample1.gif](sample1.gif)

## How to use

1. 先下載sourcecode
2. 模型從這下載，因為太大 https://drive.google.com/drive/folders/1lrTI56k9QiIfMJhG9kzNjBzJh98KCIIO  ，記得放到對應位置
3. $ python main.py --camera 0 → 開啟鏡頭
4. $ python main.py --camera .\video_1.mp4 → 預測影片
5. $ python main.py --camera .\video_1.mp4 --save_out test.avi → 儲存影片


## Model

1. sppe(骨架預測) → 太大了要另外下載 
2. stgcn(動作分析)
3. yolo(bounding box) 


## Reference

- AlphaPose : https://github.com/Amanbhandula/AlphaPose
- ST-GCN : https://github.com/yysijie/st-gcn
test