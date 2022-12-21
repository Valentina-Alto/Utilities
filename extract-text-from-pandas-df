import pandas as pd

# Load the dataframe from a .csv file
df = pd.read_csv('data.csv')

# Extract the text column from the dataframe
text = df['text']

# Iterate through the rows of the text column
for i, row in text.iteritems():
    # Save the text to a .txt file, with the file name being the index of the row
    with open(f'text_{i}.txt', 'w') as f:
        f.write(row)
