# Big_Data_with_PySpark_Projects_-_Notes

Projects and Notes (from courses mainly from DataCamp or Udemy) about Big Data with PySpark. From data analysis with sql to constructing machine learning models for classification, linear regression, and recommendation systems.  
  
Installing correctly Spark and PySpark is not an easy task, I suggest follow this tutorial  
https://www.youtube.com/watch?v=wt2wM8C2SXA&list=LL&index=16&t=332s  
Moreover, you have to define two more environmental variables: PYSPARK_PYTHON, and PYSPARK_DRIVER_PYTHON with the route to your folder where is python.exe.   
Then, the first cell that you should execute in your program is:     
import os    
import sys    
os.environ['PYSPARK_PYTHON'] = sys.executable    
os.environ['PYSPARK_DRIVER_PYTHON'] = sys.executable    
    
A suitable alternative if you will work only with your computer is to use Google Colab, it offers 12 gb of RAM. To install pyspark, you just need to run:    
!pip install pyspark py4j  
