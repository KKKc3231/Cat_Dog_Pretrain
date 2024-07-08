# Cat_Dog_Pretrain

从0实现图像分类/预训练框架，正在完善中~

支持经典图像分类预训练、CLIP蒸馏+对比学习等视觉预训练任务
- 兼容timm支持的Backbone，可任意更换Backbone
- 兼容Albentation图像增强方法
- 支持warmup+cos decay scheduler
- 自动日志记录
- 支持混淆矩阵，accuracy， f1score，mAP等评估指标
- 支持onnx格式导出(完善中)
