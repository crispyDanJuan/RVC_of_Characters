# RVC_of_Characters
Models of characters' sounds. Most of them are Japanese.

存放许多RVC模型语音包的地方，均使用Retrieval-based-Voice-Conversion-WebUI（https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI ）项目进行训练。如无特殊说明，都采用目标采样率48K、训练数据约为16分钟、训练轮数100轮。

专供懒得获取语音+训练者使用。下载后格式均为 “角色名_用于训练的RVC版本号.zip”。解压后把模型文件exp_name.pth和added_xxx.index（如有）放到weights文件夹下。刷新音色列表，检查特征检索库文件路径是否正确，然后就可以训练了。

资源文件更新均为个人训练顺序。
