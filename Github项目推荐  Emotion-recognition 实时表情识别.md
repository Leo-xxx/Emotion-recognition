## Github项目推荐 | Emotion-recognition 实时表情识别

AI研习社 [AI研习社](javascript:void(0);) *昨天*

![img](https://mmbiz.qpic.cn/mmbiz_jpg/bicdMLzImlibRiboYcgtAAFwZvvLPUlRkFmiaQ8aCfWBsYib2ic7uVBLAHBtL8m8gYWxDLRdVWaAoASYXjjYclph6NlQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**Emotion-recognition - Real time emotion recognition**

**Emotion-recognition 实时表情识别**

**Github项目地址：****https://github.com/omar178/Emotion-recognition**

![1562572716997039.png](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTwZibDGwbc506Utic6M0ENDXXLK9ScxyIR6fcqhicksZfibFXu151fymEoGB5t2ib60iaIWkSoqrasTiaIw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![1562572725707731.png](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTwZibDGwbc506Utic6M0ENDXsMZVDeeR4c2HibPtpsMYclhPK6VNLqzqtvvyhREBFu88APXzZxxweog/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## **项目描述**

我们人类的脸有着复杂的情绪，所以我们要证明我们拥有这些情绪的可能性。

### **情感识别意味着什么？**

情感识别是一种在软件中使用的技术，它将允许程序使用高级图像处理技术来“读取”人脸上的情绪。企业们一直在尝试将复杂的算法与过去十年出现的图像处理技术相结合，以便通过一个人的脸部图像或视频更多地了解他/她的感受，而不仅仅是面部可能具有的多种情绪的可能性。



## **安装**

-keras

-imutils

-cv2

-numpy



## **使用**

这个程序将创建一个通过网络摄像头显示捕获到的场景的窗口和一个表示检测到的情绪可能性的窗口。

**Demo**

- 

```
python real_time_video.py
```

你可以使用我在代码文件中写入的路径中提供的预训练模型，我已经选择了这个特定的模型，是因为它的准确性得分最高，你可以随意选择，但是在这种情况下你必须运行 train_emotion_classifier 以后的文件

#### **当然了，如果你只想运行此演示而不是从头开始训练模型，则可以跳过以下内容：**

**Train**

- 

```
python train_emotion_classifier.py
```



## **数据集**

我已经使用了以下数据集（注意需要注册登陆）：

https://www.kaggle.com/c/3364/download-all



你可以进行下载，并把csv放入 fer2013/fer2013/ 文件夹中

-fer2013情绪分类测试准确率为：66％



## **致谢**

这项工作的灵感来自于这个项目，Adrian Rosebrock的资源帮助了我很多！



## **以下工作正在进行**

在检测到的脸部旁边绘制情绪面孔。



## **问题和建议**

如果有任何问题和建议，你可以创建issue。

如果你喜欢这项工作，可以到项目上加一个 Star。

**Github项目地址：****https://github.com/omar178/Emotion-recognition**

![img](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTwZibDGwbc506Utic6M0ENDXuRib8vsl24HUiccK5JcxV9uiba1HQRib1Q8LSxlCGXtzWKrb5GIwqlEMow/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**你可能还想看**

![img](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTwZibDGwbc506Utic6M0ENDXbxd8yRzgMBnVJDUwrqDY4kp8FzYNjeic1LVt4oxFrniaKQhz89bStGdg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![img](https://mmbiz.qpic.cn/mmbiz_png/bicdMLzImlibTwZibDGwbc506Utic6M0ENDX1eEicSsXbM6E8F8uvLLiakBiahLgJkUutRT6YR7kn3qZbfOg1fhSKhQJA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**![img](https://mmbiz.qpic.cn/mmbiz_gif/bicdMLzImlibRAS3Tao2nfeJk00qqxX3axIgPV3yia4NPESGdUJEM9vsfw1O4Dg1iat7lVNAmbCMY65ia2pzfBXm5kg/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1) 点这里查看本篇相关内容**

[阅读原文](https://mp.weixin.qq.com/s?__biz=MjM5ODU3OTIyOA==&mid=2650677400&idx=2&sn=03a9d137ef412db994740af7d9d05ca0&chksm=bec21deb89b594fda05b6ecae5a48b25be7dad349a7e01f4c6f5b85ea3c15bd884a652ecc8f6&mpshare=1&scene=1&srcid=07093LYnXTeNkPP7Hq7or5RR&key=ff883993b52a2aed942602003064473782806dc81e141628affd9c1dcb20b56d86ce0cc35a7d835427c03afcf97ba7c18a01eede05e10497f67e96df6367f291c0e90aa9060e3575cdc2fc73ea973cd7&ascene=1&uin=MjMzNDA2ODYyNQ%3D%3D&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=%2Bvj8hkO2%2FJAfi%2FlPIaS%2Bz7ySCCdLQriqdK7laIlmsKs6zRWmONHUUVqoYmWx5dgS##)





![img](https://mp.weixin.qq.com/mp/qrcode?scene=10000004&size=102&__biz=MjM5ODU3OTIyOA==&mid=2650677400&idx=2&sn=03a9d137ef412db994740af7d9d05ca0&send_time=)

微信扫一扫
关注该公众号