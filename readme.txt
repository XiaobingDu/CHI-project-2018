人机交互 课程设计大作业 2018年秋季学期
1.任务描述
基于多模态生理信号的情感识别任务（Emotion Recognition based bio-signal）
在人机交互任务中利用生理信号识别情绪是至关重要的一个任务，生理信号相较于其他基于内容的情感识别任务来说更能真实反应交互任务中参与者的真实感受。本题目要求选题同学基于观看视频片段得到的脑电（EEG）数据和生理信号数据进行情感识别。
2.数据集
本任务提供两个数据集，如下：
DEAP：http://www.eecs.qmul.ac.uk/mmv/datasets/deap/readme.html
SEED：http://bcmi.sjtu.edu.cn/home/seed/download.html
两个数据集的网站如上，数据集相关说明、相关文章请自行从网站查找。
3.主要工作
使用SEED数据集中rawEEG数据或者EEG_feature数据（根据自己的需求选择）以及SEED数据集中的eye_move data或者 eye_move_feature data ，选取自己认为合适的深度学习网络模型进行基于多模态数据（两种模态：脑电数据+眼动数据）的情绪识别任务。（四分类：neutral、sad、fear and happy emotions）；最终需要验证模型的稳定性，需要在DEAP数据集（rawdata or data_feature：根据自己需求选择）上面跑该网络模型，进行多模态（两种模态：脑电数据+外周生理信号数据）的情绪识别任务。（四分类：low-valence +low-arousal、low-valence + high-arousal、high-valence + low-arousal、high-valence + high-arousal）。
一句话总结需要做的工作：在两个不同的数据集上，分别用选定的深度学习模型，完成指定的任务，情绪识别精度能够达到60%左右。

