# Bagging 介绍

+ **Bagging步骤**

   1. 采用有放回的抽样方式在样本集合中抽取N个样本，构成一个数据集；
   
   2. 按照步骤1中的方式得到M个数据集；
   
   3. 利用机器学习的方法(例如：SVM，CART，神经网络……)对得到的M个数据集，训练出M个模型；
   
   4. 将M个模型结果的集成作为最终的结果；
   
其实Bagging就是通过多个弱模型的结果，通过集成的方式来获得和强模型一样的结果。这好比三个臭皮匠顶一个诸葛亮。
  
   
+ **集成方式**

    - **回归问题**
    
        M个模型结果的均值；
 
    - **分类问题**
    
        对M个模型的结果进行投票决定，票数多的作为结果；票数一样，随机决定；


+ **代表方法** 

    + **随机森林(Random Forest) = Bagging + 决策树**




