# DataMining_UsedCarPrice

~~以下内容由ChatGPT生成~~

大数据导论大作业：数据挖掘 - 二手车交易价格预测

这个项目是我在学校大数据导论课程中的大作业。我们的目标是通过数据挖掘技术预测二手车交易价格。我们将分析二手车市场的数据，利用列名如SaleID、name、regDate、model、brand、bodyType、fuelType、gearbox、power、kilometer等多个特征，尝试建立模型以预测二手车的交易价格，通过MAE评价指标来衡量模型的预测准确度。

## 项目目标

- 分析二手车市场数据，了解影响二手车价格的因素。
- 构建预测模型，准确预测二手车的交易价格。
- 提供数据挖掘方法和技术的学习和实践经验。

## 数据集

我们使用了包含二手车交易信息的数据集，数据列名包括SaleID、name、regDate、model、brand、bodyType、fuelType、gearbox、power、kilometer等。通过对这些特征的分析和处理，我们将尝试构建一个可靠的预测模型。

## 方法

我们将采用以下方法来实现项目目标：

1. 数据清洗和预处理: 对数据进行清洗、缺失值处理、特征选择等预处理工作，以准备用于建模的数据集。
2. 特征工程: 对数据进行特征工程，提取有效特征，创建新特征以提高模型性能。
3. 模型选择和建立: 选择适当的预测模型，如线性回归、决策树、随机森林等，并通过训练和调优建立模型。
4. 模型评估和预测: 对模型进行评估，选择适当的评价指标，如MAE，并利用模型进行二手车交易价格预测。

## MAE评价指标

我们将使用MAE（Mean Absolute Error）作为模型评价的指标。MAE是回归问题常用的评价指标之一，它衡量模型预测值与实际值之间的平均绝对误差。

MAE的计算公式如下：

![MAE Formula](/images/mae_formula.png_)

其中：
- \( n \) 是样本数量。
- \( y_i \) 是实际值。
- \( \hat{y}_i \) 是模型的预测值。

MAE越小表示模型的预测误差越小，即模型预测得越准确。

在我们的项目中，我们将利用MAE评价模型的预测准确度，以便量化模型的性能并进行比较和优化。


## 结果与展望

🚗✨  这个项目将带您进入二手车交易世界，揭示其中的奥秘。

📈🛠️  我们将利用数据挖掘技术，为二手车价格预测打造强大的模型。

我们将在项目中展示预测模型的性能和效果，并讨论可能的改进方法和未来的研究方向。

欢迎查看项目并提供意见和建议！
