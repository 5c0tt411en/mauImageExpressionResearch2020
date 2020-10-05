# 画像表現研究Example projects
画像表現研究に使用するTouchDesignerのExampleです．

## Examples
### OpenCV_BrightestPoint.toe
最大輝度のpointをtrackingします．
最大なので１つだけであることに注意します．

### OpenCV_FaceTrackingMulti.toe
Face trackingします．授業時は１人のみの仕様でしたが，複数人対応しました．
正面の顔が想定されていることに注意します．

### OpenCV_TemplateMatching.toe
Template matchingで，指定した特定のtemplateが出てきたらその場所を示します．
templateと解析するテクスチャの類似度の計算を行い，そのテクスチャの輝度で判断するため，大きさは示されないことに注意します．

### OpenCV_Threshold.toe
しきい値で画像処理を行います．

### PixelInstancing.toe
Pixelの値で，オブジェクトを複製します．

### ThresholdPoint.toe
Pixelの色情報がしきい値以上のときはSampleに採用されます．