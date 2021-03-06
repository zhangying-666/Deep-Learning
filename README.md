# Deep-Learning课设
# Deep-Learning

# 背景

近年来，随着居民生活质量提高，汽车成为居民生活的一部分，预计到 2021 年，中国汽车保有量将达到 3 亿辆，安全驾驶就显得特别重要，例如近期发生公 交车坠湖，路怒人群强行超车，酒后驾驶引发悲痛事故等等，如果在这些事情发 生之前可以做一些预期提醒，就极大程度避免掉这些事故，所以汽车辅助驾驶安 全信息检测系统就显得尤为重要，更对一些新手司机提供更安全的驾车体验。

# 模型选择(Yolov5s)
![图片](https://user-images.githubusercontent.com/75561983/119947226-19ad0300-bfca-11eb-8325-10baae1d38b0.png)


# 数据来源：

飞桨AI Studio  https://aistudio.baidu.com/aistudio/index

# 训练过程：

![图片](https://user-images.githubusercontent.com/75561983/119947309-31848700-bfca-11eb-9086-da7592428190.png)


# 训练结果：
![图片](https://user-images.githubusercontent.com/75561983/119947375-3fd2a300-bfca-11eb-898c-397c1d69382f.png)


# 总结：

## 测试不够精准的原因分析

1.由于数据集太小，导致模型有很多车没见过。

2.由于threshold设置的过高，导致检测不够准确。

3.Yolov5s网络最小，速度最快，AP精度也最低。可以选择精度更高的Yolov5x
