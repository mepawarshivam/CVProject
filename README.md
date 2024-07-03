# Soyabean Leaf Disease Classification

 1 Introduction:
 Plants play a crucial role in people's daily life in the form of vegetables,
 fruits and various consumer goods. So, identifying plant leaf diseases is very
 important for farmers in enhancing agricultural productivity. But, due to a wide
 variety of diseases, leaf disease identification by the human eye is
 time-consuming, difficult and also less accurate. Therefore, there is a need for
 Automatic Leaf Disease Identification techniques which helps farmers to identify
 various diseases with less effort, less time and more accuracy. These techniques
 also help in healthy monitoring of fields that ensure quality agricultural products.
 Given a leaf, identify the disease that leaf has, among various diseases
 with high accuracy using image processing techniques.
 2 Method:
 ● 1. Predict the disease for a leaf that is not yet identified.
 ● 2. We want to find probabilities of leaf having various diseases so that we
 can choose high probability as predicted disease (Softmax).
 ● 3. Minimize the difference between predicted and actual disease
 (Categorical Cross Entropy).
 ● Constraints:
 1. No strict latency concerns.
 3 Experiments:
 3.1 Dataset:
 The dataset contains leaf images of soyabean plant. Data is collected from
 Digipathos Repository.
 Data source: https://www.digipathos-rep.cnptia.embrapa.br/jspui/
 (https://www.digipathos-rep.cnptia.embrapa.br/jspui/)
3.2 Evaluation metrics:
 ● Accuracy - It is the ratio of no. of true predictions to the total no. of
 predictions.
 ● Confusion Matrix - Matrix(table) that helps in visualizing the performance of
 model.
