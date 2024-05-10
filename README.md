This study presents a comprehensive investigation into vehicle classification, employing a combination of convolutional neural network (CNN) architectures, machine learning models, and swarm intelligence-based optimization techniques. Leveraging image augmentation methods and assessing prominent CNN architectures such as **VGG16 and ResNet**, we determined that VGG16 features offer superior performance for feature extraction. Subsequently, six different machine learning models, including **SVM, Logistic Regression, XGBoost, Random Forest, Decision Tree, and KNN**, were employed for classification tasks. Swarm optimization techniques, including **Particle Swarm Optimization, Ant Colony Optimization, and Firefly Optimization**, were then utilized to fine-tune hyperparameters for each model.

After optimization, Logistic Regression, SVM, and XGBoost emerged as top performers, showing significant accuracy improvements. Logistic Regression achieved 96.37%, SVM reached 95.87%, and XGBoost attained 90.42%, compared to their pre-optimized accuracies of 92.74%, 74.75%, and 86.13%, respectively. To further enhance accuracy, a **SLEM-STACK ensemble** was formed, combining these models with a meta-classifier **MLPClassifier**, featuring three hidden layers with 100, 50, and 50 neurons, respectively.

**ARCHITECTURE OF SLEM-STACK MODEL**
![SLEM STACK](https://github.com/Saideepika-G/Project-Phase-II-SLEMSTACK/assets/82448488/b2c1c11a-b8f2-4f4e-81cc-0c5715fa6040)


Through this stacking approach, **SLEM-STACK** achieved an accuracy boost, reaching **97.03%**. This ensemble strategy capitalized on the strengths of each base classifier while mitigating their individual weaknesses, resulting in a more robust and accurate classification system. Overall, our findings underscore the potential of ensemble technique in significantly improving classification accuracy, especially when combined with CNN architectures and swarm optimization techniques. This integrated approach holds promise for advancing vehicle classification and other related machine learning tasks in various domains.
