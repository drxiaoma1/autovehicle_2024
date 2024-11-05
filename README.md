# autovehicle_2024
My trial of autovehicle using AI method

### 小车AI巡线
文件夹model_training解压后得到需要的代码文件，在文件夹中上传目标视频并重命名为video后就可以开始标注

运行originbot_data来标注数据，尽量保持红点在车道中间，采集百余组数据即可

运行originbot_train来训练模型，得到.pth模型文件

运行originbot_onnx来转换格式，得到.onnx模型文件

可以运行originbot_test，检查模型训练效果

可以查看第6周实验参考书来了解详细内容
