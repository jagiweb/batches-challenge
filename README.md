# batches-challenge

Write a Ruby function that takes an input parameter of a CSV file. It should print the total 
input ingredient mass received each month, one month per line. The CSV contains received 
batches of a product in the format below:

batch_id,date,supplier,mass
23,2019-01-01,Foo Inc,12.1
24,2019-01-01,Bar Inc,2.3
25,2019-01-02,Baz Ltd,40.7

You can assume:
dates are formatted in international format as yyyy-mm-dd
mass is in kg
the whole file represents 1 year