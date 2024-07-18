# AITools-Release
快速上手深度学习。
|  | 主要参数解释 |
| --- | --- |
| ![image.png](https://cdn.nlark.com/yuque/0/2024/png/22722684/1721264388084-87e7400e-afac-40bd-b01c-94f06f423faa.png#averageHue=%23e3ecf5&clientId=u863adb93-9641-4&from=paste&height=1144&id=ub651a6cb&originHeight=1258&originWidth=364&originalType=binary&ratio=1.100000023841858&rotation=0&showTitle=false&size=376209&status=done&style=none&taskId=uc7844b87-3996-4c75-8aee-0ec18c03598&title=&width=330.9090837368297) | "硬件选择"：有GPU就用GPU；

"类别数量"：没有特殊情况，设1就好了；
"epochs"：代表训练的次数，越大训练时间越久；

"batch_size"：可选择8、16、32，2的指数倍，如果我们显存不大，就设置小点；

"image_size"：训练图像的大小，必须是32的倍数；

"开启验证"：开启验证后训练速度会减半，默认可以不开启；

"数据增广"：通过一系列的图像变换操作，可以增强AI模型的抗干扰能力；

"模型评估"：点击开始评估，会对比模型的识别结果与我们的标注是否一致；

"模型导出"：有CPU、GPU两种方式。 |
| ![image.png](https://cdn.nlark.com/yuque/0/2024/png/22722684/1721203139348-26989516-d434-49b1-9c2f-8f1428b8d775.png#averageHue=%23e7e7e7&clientId=uec75fc35-5b12-4&from=paste&height=563&id=R19H8&originHeight=619&originWidth=305&originalType=binary&ratio=1.100000023841858&rotation=0&showTitle=false&size=21186&status=done&style=none&taskId=ue753d4f6-db9b-4b7c-89e1-e0ec418af12&title=&width=277.2727212630029) | 点击“高级参数”后我们会看到这个页面。

"模型选择"：AITools中目前配备了model1~8，八个AI模型，“model1”是AITools中的最小模型，通常能满足各个现场，如果有一些训练很困难的数据，可以尝试“model2”或其他更好的模型，“model2”效果已经明显好于“model1”；

"训练线程"：如果电脑性能不够优秀，设置1就行，如果我们性能优秀，比如你有一台RTX 3080ti显卡的电脑，可以设置为4，训练速度能快一些；

"加载预训练模型"：默认勾着就行；

"获取最新版本"：点击即可弹到下载页面。
 |
| ![image.png](https://cdn.nlark.com/yuque/0/2024/png/22722684/1721203992204-c6017f4c-86f5-4bc5-970a-6ebfc6f4a8b8.png#averageHue=%238bcf83&clientId=uec75fc35-5b12-4&from=paste&height=212&id=u16556f80&originHeight=233&originWidth=346&originalType=binary&ratio=1.100000023841858&rotation=0&showTitle=false&size=59937&status=done&style=none&taskId=u25727816-70a5-4bd5-b304-89dd2583bcb&title=&width=314.54544772786556) | "自动标注"：开启后，双击”标注模块“的空白部分，即可自动标注；

"使用预设标签"：默认是1，也就是缺陷的类别，通常我们可以直接用一个类别。 |
| ![image.png](https://cdn.nlark.com/yuque/0/2024/png/22722684/1721264175281-67cf51e0-8469-4aa6-885a-7994e759356f.png#averageHue=%2394b4aa&clientId=u863adb93-9641-4&from=paste&height=122&id=u574e663d&originHeight=134&originWidth=410&originalType=binary&ratio=1.100000023841858&rotation=0&showTitle=false&size=77801&status=done&style=none&taskId=u859754b3-c654-4533-8c63-c9d6ed52081&title=&width=372.72726464862683) | 当我们点击了“开始评估”之后，文件列表将会自动列出AI识别结果与标注结果不一致的图像。

双击文件，可打开原图。 |

