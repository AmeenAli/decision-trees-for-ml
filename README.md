# Decision Trees for Machine Learning

This is the repository of Decision Trees for Machine Learning online course. In this course, the following algorithms will be covered. All project is going to be developed on Python (3.6.4), and neither out-of-the-box library nor framework will be used to build decision trees.

1- ID3 - [Documentation](https://sefiks.com/2017/11/20/a-step-by-step-id3-decision-tree-example/)

2- C4.5 - [Documentation](https://sefiks.com/2018/05/13/a-step-by-step-c4-5-decision-tree-example/)

3- CART (Classification And Regression Trees) - [Documentation](https://sefiks.com/2018/08/27/a-step-by-step-cart-decision-tree-example/)

4- Regression Trees (CART for regression) - [Documentation](https://sefiks.com/2018/08/28/a-step-by-step-regression-decision-tree-example/)

5- Random Forest - [Documentation](https://sefiks.com/2017/11/19/how-random-forests-can-keep-you-from-decision-tree/)

Just call the [decision.py](/python/decision.py) file to run the program. You might want to change the running algorithm. You just need to set algorithm variable.

  algorithm = "ID3" #Please set this variable to ID3, C4.5, CART or Regression
  
Moreover, you might want to apply random forest. Please set this to True in this case.

  enableRandomForest = False

Finally, you can change the data set to build different decision trees. Just pass the file name, and its column names if it does not exist.

  df = pd.read_csv("car.data"
    ,names=["buying","maint","doors","persons","lug_boot","safety","Decision"] #column names can either be defined in the source file or names parameter
  )
