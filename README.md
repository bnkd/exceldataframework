# exceldataframework

# BASE

This is a Python script made using pandas library

# Working of the Script

This Python script allows to take data from a csv, and get the corresponding equating from another csv and store it in a new csv file. 


# Demonstration

Let's Say there is a CSV file with Coloumns:- items & Selling_price  named as consumer.csv and another CSV named as backend.csv with Coloumns items , cost_price, HSN code , Tax Slab , Supplier.

<img width="339" alt="Screenshot 2024-05-13 at 8 07 29 PM" src="https://github.com/bnkd/exceldataframework/assets/107197651/31ddaebc-8b6d-4886-87c3-c7719000a6cc">


consumer.csv


<img width="637" alt="Screenshot 2024-05-13 at 8 17 06 PM" src="https://github.com/bnkd/exceldataframework/assets/107197651/ac96e2ec-1ec9-430d-8631-4078418f1746">



backend.csv




The Goal is to create a csv file named as req.csv with both these files

With the above script you will be able to perform the required Task



<img width="578" alt="Screenshot 2024-05-13 at 8 32 05 PM" src="https://github.com/bnkd/exceldataframework/assets/107197651/c935b9e6-d972-4e7f-a6e1-2ae0fed698f5">





rec.csv





# Relavance

when the data which we are requested to get the details from the second csv file is not orderd or only partial data out is required we can easily get it using this tool



# About Code
I Have uploaded the code that i used to demonstrate the example which can be easily be  modified to do the required work,
you can merge multiple CSV file by adding more 

detail_df = pd.read_csv(".csv")

statements and changing the code appropriately

I have Uploaded the code as a Python Notebook for easy error detection.

