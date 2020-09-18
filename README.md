# SQL_Injection_Detection

Dataset :- https://www.kaggle.com/syedsaqlainhussain/sql-injection-dataset
In this We have two columns named Sentence and Label, Where sentence represents SQL query and Label represents weather that query leads to injection or not.
First we have modified text data in numeric format using CountVectorzier which convert text data into  vector of token count, i.e. for each word we get its corrosponding count in the sentence.
Then we converted this vector in dataframe and combined with our dataset.
then performed various classification algorithms to find better accuracy.
