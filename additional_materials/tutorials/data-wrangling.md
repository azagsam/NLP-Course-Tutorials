### Exercise 1: Introduction to data wrangling

- Import data
- Subset observations and variables
- Transform existing values (e.g., lowercase text columns)
- Create new variables (e.g., count number of vowels in text columns, assign examples IDs)
- Drop variables
- Save dataframe to disk in various formats (tsv, json, …)

### Exercise 2: Working with text files

- Download WSC dataset: https://drive.google.com/file/d/1pAFXnjHyeRm9TGV9mknM25f7AvS8UZ4-/view?usp=share_link
- Read files and store them into one dataframe (preserve train, test, and val split info)
- Count label values: What is the distribution of the target variable?
- Create new variables that store information about tagged words (index & word)
- Create a new variable that stores text without tags
- Save to disk 3 files in json lines format (train.jsonl, val.jsonl, test.jsonl) 