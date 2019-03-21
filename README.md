# exam_1_activity
# 验证activity的周期
姓名：吴焰辉 学号123012016055

### 1打开app
在log可以看到依次调用了onCreate（），onStart（），onResume（）三个函数
![Image text](https://github.com/w814698066/exam_1_activity/blob/master/image/1.png)
### 2后台运行app
依次调用了onPause（），onStop（）两个函数
![Image text](https://github.com/w814698066/exam_1_activity/blob/master/image/2.png)
### 3回到app
 调用了onRestart（），onStart（），onResume（）
![Image text](https://github.com/w814698066/exam_1_activity/blob/master/image/3.png)
