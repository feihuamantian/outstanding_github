## (1) 文本识别和分类模型
### introduce:
          1) 本项目采用Keras和Keras-bert实现文本多分类任务。
           2)使用THUCNews数据集进行训练与测试，10个分类，每个分类6500条数据。 类别如下： 体育, 财经, 房产, 家居, 教育, 科技, 时尚, 时政, 游戏, 娱乐 数据集划分如下： 训练集: 5000 * 10 测试集: 1000 * 10
           3) 代码结构
            ├── chinese_L-12_H-768_A-12（BERT中文预训练模型）
            │   ├── bert_config.json
            │   ├── bert_model.ckpt.data-00000-of-00001
            │   ├── bert_model.ckpt.index
            │   ├── bert_model.ckpt.meta
            │   └── vocab.txt
            ├── data（数据集）
            │   └── sougou_mini
            │       ├── test.csv
            │       └── train.csv
            ├── label.json（类别词典，生成文件）
            ├── model_evaluate.py（模型评估脚本）
            ├── model_predict.py（模型预测脚本）
            ├── model_train.py（模型训练脚本）
            └── requirements.txt
github url: https://github.com/percent4/keras_bert_text_classification
