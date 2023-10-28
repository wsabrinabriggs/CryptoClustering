# CryptoClustering

Hello and thank you for your time.
Coding Help:
1. How to set the index of a dataframe to a column
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html
2. How to add column in dataframe from list
https://stackoverflow.com/questions/26666919/add-column-in-dataframe-from-list
3. How to avoid memory leak when dealing with KMeans for example in this code, I am trying to find the best WCSS to use in KMean clustering
https://stackoverflow.com/questions/69596239/how-to-avoid-memory-leak-when-dealing-with-kmeans-for-example-in-this-code-i-am

Help from BCS:
1. You can also experiment with this # Assuming you have a DataFrame named df with the "coin_id" column as the index
# Create a new DataFrame and set the "coin_id" column as the index
new_df = new_df.set_index(df.index)

2. in this case, try using .tolist() on k_4 before you add the new column
 
Support from Outside Code Source(s):
1. https://github.com/Asalvs/CryptoClustering/blob/main/.ipynb_checkpoints/Crypto_Clustering_starter_code-Copy1-checkpoint.ipynb
