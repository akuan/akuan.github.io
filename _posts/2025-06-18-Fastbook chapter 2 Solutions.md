# Questionnaire
1. Provide an example of where the bear classification model might work poorly in production, due to structural or style differences in the training data.
   ```
   There are many cases that the bear classification mode could fail,especially if these cases were not represnted in the training data:
    . The bear is covered by bushes or trees, making it hard to see.
    . The bear is in a different environment than the training data, such as a snowy landscape
    . Nighttime images are passed into the model.
    . Low-resolution images are passed into the model.
    . The bear is far away from the camera, making it hard to see.
    . The bear training dataset is highly biased towards one type of featuress(eg. color)
   ```
2. Where do text models currently have a major deficiency?
   ```
   Text models currently have a major deficiency in understanding context and nuance, particularly in complex or ambiguous sentences.
   ```   

4. What are possible negative societal implications of text generation models?
5. In situations where a model might make mistakes, and those mistakes could be harmful, what is a good alternative to automating a process?
6. What kind of tabular data is deep learning particularly good at?
7. What's a key downside of directly using a deep learning model for recommendation systems?
8. What are the steps of the Drivetrain Approach?
9. How do the steps of the Drivetrain Approach map to a recommendation system?
10. Create an image recognition model using data you curate, and deploy it on the web.
11. What is DataLoaders?
12. What four things do we need to tell fastai to create DataLoaders?
13. What does the splitter parameter to DataBlock do?
14. How do we ensure a random split always gives the same validation set?
15. What letters are often used to signify the independent and dependent variables?
16. What's the difference between the crop, pad, and squish resize approaches? When might you choose one over the others?
17. What is data augmentation? Why is it needed?
18. What is the difference between item_tfms and batch_tfms?
19. What is a confusion matrix?
20. What does export save?
21. What is it called when we use a model for getting predictions, instead of training?
22. What are IPython widgets?
23. When might you want to use CPU for deployment? When might GPU be better?
24. What are the downsides of deploying your app to a server, instead of to a client (or edge) device such as a phone or PC?
25. What are three examples of problems that could occur when rolling out a bear warning system in practice?
26. What is "out-of-domain data"?
27. What is "domain shift"?
28. What are the three steps in the deployment process?
