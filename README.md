## Dreams Of Anomalies

This project accomplishes the following<br>

1. Set up a data science project structure in a new git repository in your GitHub account<br>
2. Download the benchmark data set from<br>
https://www.kaggle.com/boltzmannbrain/nab or
https://github.com/numenta/NAB/tree/master/data
3. Load the one of the data set into panda data frames<br>
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis<br>
5. Build one or more anomaly detection models to determine the anomalies using the other columns as features<br>
6. Document your process and results<br>
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub<br>



## Results

3 sigma is a naive approach that detected some anomalies, however it wasn't very effective because the data wasn't very normal.<br>
Isolation forest was extremely effective when compared to 3 sigma detection which is shown by detecting a reasonable amount of truly anomalous data.
