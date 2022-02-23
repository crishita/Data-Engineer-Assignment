# Data-Engineer-Assignment
1. I have used Google Colab to do this assignment. The code is in the form of python
notebook (.ipynb) and in order to run this notebook, simply upload it on google
colab and run the cells.
2. The output is already saved in the notebook and will be visible once you upload it
on google colab.
3. To read the file, I mounted the google drive with the notebook. In order to run the
code on your system, create a folder in your google drive, name it as “assign” and
upload the csv file provided to us on this folder. Then by simply running the code,
you will be able to view the output.

Questions Answered:
1. Products without prices
2. Count of products without prices and with prices in each Product Type, Category, Level 1
3. Correct Product Prices in the correct format (eg: $56) wherever possible and separate
them into currency and value columns.
4. List out the categories with average price of product.

I have solved all the above problems along with the graphs to depict the given data. In
the 3rd question, I have first filtered the unfiltered price string for those products for
which the filtered price string was null (NaN). I did this by using the .word_tokenize()
function of nltk library. After filtering the unfiltered price, I converted the price string into
the given format (eg: $56) and then separated the columns for currency and price.
In the 4th question , I have used the .groupby() function to list down the categories along
with the average price of the products belonging to that category.
In preprocessing, I checked for duplicates and dropped all of them.

Link to the data - https://drive.google.com/drive/folders/1an6sC6DHUp1ADhTZZVkGKZzTWySEqjxI?usp=sharing
