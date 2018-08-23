# Machine Learning Crash Course Homework

## 1）Pandas 简介 
[作业](https://github.com/hoshinotsuki/ML_google/blob/master/1.intro_to_pandas.ipynb "作业")  

* 大致了解 pandas 库的 DataFrame 和 Series 数据结构  
* 存取和处理 DataFrame 和 Series 中的数据  
* 将 CSV 数据导入 pandas 库的 DataFrame  
* 对 DataFrame 重建索引来随机打乱数据  
* pandas 是一种列存数据分析 API。有关更完整的参考，请访问 pandas 文档网站，其中包含丰富的文档和教程资源。  

## 2）使用 TensorFlow 的起始步骤
此练习介绍了线性回归。

[作业](https://github.com/hoshinotsuki/ML_google/blob/master/2.first_steps_with_tensor_flow.ipynb "作业")  

* 学习基本的 TensorFlow 概念  
* 在 TensorFlow 中使用 LinearRegressor 类并基于单个输入特征预测各城市街区的房屋价值中位数  
* 使用均方根误差 (RMSE) 评估模型预测的准确率  
* 通过调整模型的超参数提高模型准确率  

## 3）合成特征和离群值
此练习介绍了合成特征，以及输入离群值会造成的影响。

[作业](https://github.com/hoshinotsuki/ML_google/blob/master/3.synthetic_features_and_outliers.ipynb "作业")  
[源码](https://github.com/hoshinotsuki/tensorflow-gpu-test/blob/master/synthetic_features_and_outliers.py "源码")

* 创建一个合成特征，即另外两个特征的比例  
* 将此新特征用作线性回归模型的输入  
* 通过识别和截取（移除）输入数据中的离群值来提高模型的有效性  

## 4）Validation
As in the prior exercises, we're working with the California housing data set, to try and predict median_house_value at the city block level from 1990 census data.  

[作业](https://github.com/hoshinotsuki/ML_google/blob/master/4.validation.ipynb  "作业")    

* Use multiple features, instead of a single feature, to further improve the effectiveness of a model  
* Debug issues in model input data  
* Use a test data set to check if a model is overfitting the validation data  

