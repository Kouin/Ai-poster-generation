
# 命名实体
### 目标 对车展文本中时间、地点、举办方


### 数据收集标注


### 数据训练
`python BERT_NER.py --data_dir=data/ --bert_config_file=checkpoint/bert_config.json --init_checkpoint=checkpoint/bert_model.ckpt --vocab_file=vocab.txt --output_dir=./output/result_dir/
`
### 数据测试
