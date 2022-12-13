# boass_model_package

To run the following package you should:

1. Create a folder where you can have your data and python file 
2. In the folder, have the data in the 'CSV' format, where the first column will represent time and the second column value, without headings 


<img width="231" alt="Capture" src="https://user-images.githubusercontent.com/97521214/207386010-1ce6b272-e396-4139-9c10-79e59fe9ab13.PNG">


3. Create a python file and in the file run the following commands
- !pip install bass-model-package
- from bass_model_package.bass_model_package import Bass_Model
- model = Bass_Model("smartphones.csv")

Now you can use the following methods:

- model.fit()  # fitting the data
- model.predict() # getting the prediction
- model.plot_pdf() #  ploting predicted pdf against the actual sales data
- model.plot_cdf() # ploting predicted cdf 
- model.summary() # getting the summary


