---
title: "Project proposal"
format: 
  html:
    toc: true
    toc-title: Contents
    code-fold: show
    self-contained: true
jupyter: python3
---
## Instructions {-}

1. Please answer the following questions as part of your project proposal.

2. Write your answers in the *Markdown* cells of the Jupyter notebook. You don't need to write any code, but if you want to, you may use the *Code* cells.

3. Use [Quarto](https://quarto.org/docs/output-formats/html-basics.html) to print the *.ipynb* file as HTML. You will need to open the command prompt, navigate to the directory containing the file, and use the command: `quarto render filename.ipynb --to html`. Submit the HTML file.

4. The project proposal is worth 8 points, and is due on **27th January 2023 at 11:59 pm**. 

5. You must make one submission as a group, and not individually.

6. Each team member must have at least **one commit** on the team's github repository. No points will be awarded to the team member(s) with no commits.

7. Share the link of your project's GitHub repository [here](https://docs.google.com/spreadsheets/d/1khao3unpj_vsx4kOSg_Zzo77YK1UWL2w73Oa0aAirOo/edit#gid=0).
# 1) Team name
Mention your team name.

*(0 points)*
# 2) Member names
Mention the names of your team members.

*(0 points)*
# 3) Link to the GitHub repository
Share the link of the team's project repository on GitHub.

Also, put the link of your project's GitHub repository [here](https://docs.google.com/spreadsheets/d/1khao3unpj_vsx4kOSg_Zzo77YK1UWL2w73Oa0aAirOo/edit#gid=0).

We believe there is no harm in having other teams view your GitHub repository. However, if you don't want anyone to see your team's work, you may make the repository *Private* and add your instructor and graduate TA as *Colloborators* in it.

*(0 points)*
# 4) Topic
Mention the topic of your course project.

*(0.25 points)*
# 5) Problem statement
Explain the problem statement. The problem statement must include:

1. The problem

2. Is it a regression or classification problem or a combination of both?

3. Is it an inference or prediction problem or a combination of both?

4. How will you assess model accuracy?

  - If it is a classification problem, then which measure(s) will you optimize for your model – precision, recall, false negative rate (FNR), accuracy, ROC-AUC etc., and why?
  - If it is a regression problem, then which measure(s) will you optimize for your model – RMSE (Root mean squared error), MAE (mean absolute error), maximum absolute error etc., and why?

5. What techniques do you think you may need to use to improve your model? If you have too many variables, some of which are  correlated or collinear, you may need to do variable selection *(techniques for variable selection that you will learn later in the course - stepwise regression, lasso, ridge regression)*. If the variables do not have a linear relationship with the response, or if some of the modeling assumptions are not satisfied, you may need to transform the predictors and/or the response (variable transformation) to obtain a better fit.

*(5 points)*
# 6) Data sources

What data sources will you use, and how will the data help answer the questions? Explain.

If the data is open source, share the link of the data.

*(1 point)*
# 7) Stakeholders
Who are the stakeholders, and how will your project benefit them? Explain.

*(1 point)*
# 8) Results
What kind of results do you expect? 

How much accuracy is required / desired in your model (based on the metric(s) chosen in question 5), such that it is useful to the stakeholders and why?

**Hint:** If it is a classification model, then your model must be at least better than random classification. If it is a regression model, then your model must be at least better than trivial models, such as the one with only the intercept term.

*(0.5 point)*
# 9) Work-split
How do you plan to split the project work amongst individual team members?

*(0.25 point)*
