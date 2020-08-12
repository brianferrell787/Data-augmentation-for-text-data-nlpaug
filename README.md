# Data-augmentation-for-text-data-nlpaug
To help fix a small dataset problem, I implemented data augmentation techniques to synthetically increase the amount of data we have. I then trained the deep learning network on the augmented data and not the original set(that became the test set). This helped with the overall performance of the algorithim, and it was honestly really fun to do. 

# Suggestions: 
My suggestion would be to read the documentation and figure out how to best implement these skills on your specific problem. I use Google Colab because of the free GPU, and you can make things run a little bit faster. In the code implementation you will see which model actually ran faster than others  

# **Documentation**:
(https://nlpaug.readthedocs.io/_/downloads/en/latest/pdf/)

# **How to Download**:
I have code at the end of it that will download the file as a excel file. You can very easily switch that to a JSON file if needed
Looks like this:
```python
try:
  from google.colab import files
except ImportError:
   pass
else:
  training_df.to_excel('training_df.xlsx') 
  files.download('training_df.xlsx')
```

# **Data Aug Example**:
![Alt text](Dataaugexample.jpg?raw=true "Title")
