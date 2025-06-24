# solutions
1. Provide an example of where the bear classification model might work poorly in production, due to structural or style differences in the training data.
   > There are many cases that the bear classification mode could fail,especially if these cases were not represnted in the training data:
    . The bear is covered by bushes or trees, making it hard to see.
    . The bear is in a different environment than the training data, such as a snowy landscape
    . Nighttime images are passed into the model.
    . Low-resolution images are passed into the model.
    . The bear is far away from the camera, making it hard to see.
    . The bear training dataset is highly biased towards one type of featuress(eg. color)
   
2. Where do text models currently have a major deficiency?
   > Text models is currently not good at generating correct responses. We can't currently combie a knowledge base with a deep learning model for generating correct natural language responses.

3. What are possible negative societal implications of text generation models?
   >One possible negative societal impications of text generation models is to spread disinformation,create unrest, and encourage conflict.
4. In situations where a model might make mistakes, and those mistakes could be harmful, what is a good alternative to automating a process?
   >The predictions of the model could be reviewed by a human experts for them to evaluate the results and determine what is the best next step. This is espicially true for applying machine learning for medical diagnoses. For example, a machine learning model for identifying strokes in CT scans can alter high priority cases for expedited reviewm, while other cases are still send to rradiologists for review.Or other models can also augument the medical professional's abilities, reducing risk but still improving efficiency of the workflow. For example, deep learning models can provide useful measurements for radiologists or pathologists.
5. What kind of tabular data is deep learning particularly good at?
   > Deep learning is particularly good at tabular data that colums containing natural language and high-cardinality categorical columns. i.e., something that cotains a large number of discrete choices,such as zip code or product ID.
6. What's a key downside of directly using a deep learning model for recommendation systems?
   > The key downside of directly using a deep learning model for recommedation is that they only tell what products a particular user might like, rather than what recommendations would be helpful for a user. For instance, if the user is already familiar with the products, or if they are simply different packagings of products they have already purchased (such as a boxed set of novels, when they already have each of the items in that set). 
7. What are the steps of the Drivetrain Approach?
   > The steps of the Drivetrain Approach are:
   1. Define objective.
   2. Determine the controllable variables.
   3. Collect data.
   4. Build models.
8. How do the steps of the Drivetrain Approach map to a recommendation system? 
   > The objective of recommendation engine is to drive additional sales by surprising and delighting the customer with recommendations of items the would not have purchased without the recommendation. The lever is the ranking of the recommendations. New data must be collected to generate recommendations, that will cause new sales. This will require conductiing many randomized experiments in order to collect data about a wide range of recommendations for a wide range fo customers. This is a step that few organizations take;
   but without it, you don't have the information you need to actually optimize recommendations based on your ture objectvie（more sales!）
9.  Create an image recognition model using data you curate, and deploy it on the web.
10. What is DataLoaders?
11. What four things do we need to tell fastai to create DataLoaders?
    > DataLoaders is a fastai class that stores multiple DataLoader objects when user pass to it, normally a train and a valid.
12. What does the splitter parameter to DataBlock do?
    > What kinds of data we are working with
How to get the list of items
How to label these items
How to create the validation set
1.  How do we ensure a random split always gives the same validation set?
2.  What letters are often used to signify the independent and dependent variables?
3.  What's the difference between the crop, pad, and squish resize approaches? When might you choose one over the others?
4.  What is data augmentation? Why is it needed?
5.  What is the difference between item_tfms and batch_tfms?
6.  What is a confusion matrix?
7.  What does export save?
8.  What is it called when we use a model for getting predictions, instead of training?
9.  What are IPython widgets?
10. When might you want to use CPU for deployment? When might GPU be better?
11. What are the downsides of deploying your app to a server, instead of to a client (or edge) device such as a phone or PC?
12. What are three examples of problems that could occur when rolling out a bear warning system in practice?
13. What is "out-of-domain data"?
14. What is "domain shift"?
15. What are the three steps in the deployment process?
