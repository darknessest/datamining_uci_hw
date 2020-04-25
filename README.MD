# 数据挖掘期末大作业——基于UCI数据

## 通知
- 可以把`default.ipynb`作为模版
- 每个人请先 commit->push 到自己的分支
- 请不要上传私人文档，包括 .文件夹 （比如 `.ipynb_checkpoints`, `.idea`等等）。推荐使用`.gitignore`
- 当前做的任务在[Projects](https://github.com/darknessest/datamining_uci_hw/projects/1)里 拉到'In progress'， 做完的话 到'Done'
- 如果遇到任何别的任务，别忘记在[Projects](https://github.com/darknessest/datamining_uci_hw/projects/1)里记录下来

## 合作者
曾嘉宝，陈丰铧，博雅力

## 数据集
- Multifly Feature(mfeat)
- Sonar
- Haberman
- Contraceptive(cmc)

## 数据属性
### 1. [mfeat](http://archive.ics.uci.edu/ml/datasets/Multiple+Features):
手写的0-9十个数字的分类，UCI提供了6个相关数据子集，我们选择了其中3个
160*10个实例，按0-9排序（label隐式表达）
    
mfeat-pix: 240 pixel averages in 2 x 3 windows; 15*16 pixs; 240 attributes

mfeat-zer: 47 Zernike moments;47 attributes

mfeat-mor：6 morphological features.

### 2. sonar
classification of sonar signals

Instance: 208 = 111 （Metal cylinder ）+ 97 Rocks

Each pattern is a set of 60 numbers in the range 0.0 to 1.0. 


### 3. Haberman
The survival of patients who had undergone surgery for breast cancer.

Instance:306  

Attribute： 3+1

1 = the patient survived 5 years or longer  
       
2 = the patient died within 5 year


### 4. [cmc](https://archive.ics.uci.edu/ml/datasets/Contraceptive+Method+Choice)
1473：9+1
1. Wife's age (numerical)
2. Wife's education (categorical) 1=low, 2, 3, 4=high
3. Husband's education (categorical) 1=low, 2, 3, 4=high
4. Number of children ever born (numerical)
5. Wife's religion (binary) 0=Non-Islam, 1=Islam
6. Wife's now working? (binary) 0=Yes, 1=No
7. Husband's occupation (categorical) 1, 2, 3, 4
8. Standard-of-living index (categorical) 1=low, 2, 3, 4=high
9. Media exposure (binary) 0=Good, 1=Not good
10. Contraceptive method used (class attribute) 1=No-use, 2=Long-term, 3=Short-term

## 分工
曾嘉宝：

陈丰铧：

博雅力：