## g-b-probability

### This project refers to the gaussian and binomial probability distribution.
  - It is a pyhton package.
  - Built by using basic object oriented programming in python
  - This is the project for calculating Gaussian and Binomial probability distribution
  - It also shows the distribution charts as histograms and bar charts.


**This can be installed from pypi.**
- **installation command: pip install g-b-probability**

### Usage guide
- install the package
- Import the desired function
  ```from g_b_probability import Binomial, Gaussian```
  - Then Create a object variable for desired for distribution
    - For example, for Gaussian distribution      
    ``` gaus = Gaussian(20, 5), # where mean=20, std= 5``` 
    - For Binomial distribution    
    ``` bino = Binomial(), # where default mean=10, std= 2.23, probability,p = 0.5, numbers,n = 20 ```
    - To read data from text file     
    ``` bino.read_data_file('numbers_binomial.txt')```    
    ``` bino.replace_stats_with_data() ```   
    ``` bino.plot_bar()   #For showing the data bar for inputs```   
    ``` bino.plot_bar_pdf() #For showing the data of the distribution```

