### AIOps-2018-KPI-TSAD

这个仓库主要包含对于[AIOps-2018-KPI异常检测竞赛](http://iops.ai/competition_detail/?competition_id=5&flag=1)
的[决赛数据集](https://github.com/NetManAIOps/KPI-Anomaly-Detection/tree/master/Finals_dataset)的相关预处理结果

* separate_data 将原始决赛数据集按ID划分，保存为29条单独的时序数据
    * separate_train_data 对应[决赛训练集](https://github.com/NetManAIOps/KPI-Anomaly-Detection/blob/master/Finals_dataset/phase2_train.csv.zip)
    * separate_test_data 对应[决赛测试集](https://github.com/NetManAIOps/KPI-Anomaly-Detection/blob/master/Finals_dataset/phase2_ground_truth.hdf.zip)
    * display_no_missing 相应时序数据的可视化

原始数据集下载地址：https://github.com/NetManAIOps/KPI-Anomaly-Detection