# superhero-generator

## Summary
Created a character level language model that will predict the next character for a given input sequence. <br />
In order to get a new predicted superhero name, a seed input is given - this can be a single character or a sequence of characters <br />
The model will then generate the next character that it predicts should be after the input sequence <br />
This character is then added to the seed input to create a new input, which is then used again to generate the next character, and so on.

## Process
Filtered out punctuation from the superhero text file and converted the names to sequences. <br/ >
Padded sequences and transformed it into a 2D array. <br/ >
Split the data into training and testing data. <br/ > 
Built and trained a Sequential model. <br/ > 
