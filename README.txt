segofSegmentation.py包含三个主要functions，分别是：

IoU,accuracy=scoreSegPath(path,num_class):针对路径中pred和anno文件夹中的结果进行对比
IoU,accuracy=scoreSegSingle(imPred,imAnno,num_class)：对单张结果分析
IoU,accuracy=scoreSegNumpy(npPred,npAnno,num_class)：对数组结果分析

IoU：对于所有类别的交并比
accuracy：精确度
path：路径
num_class：语义分割类别
imPred：预测的结果图（png格式最好）
imAnno：标注图
npPred：预测图片的numpy数组
npAnno：标注图片的numpy数组
