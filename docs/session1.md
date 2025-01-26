# I. Python Programming Concepts.

## Installing

Visit python.org/downloads and download the latest release for your OS.
![download page](./assets/download_python.png)

## hello world!

```
print('hello world')

>>> hello world
```

## Python Compiler & IDE

### Jupyter Notebook & Anaconda
Visit 

### Google Colab
Google Colab is a cloud-based notebook service for running heavy computations like bioinformatics tasks. Also great for data analysis, machine learning & visualizations.

### VS Code/ PyCharm/ Spyder
These support Python development with features like syntax highlighting, formatting, debugging, code auto-completion, package management & more.

### Comments
We use comments to help others understand our code better. We also forget what we wrote a month/year ago, so comments help us remember why we did something.

```
# takes text files and converts them to pdf

Python code here....
```

## Variable
Variables hold data. Assignment is done right-to-left with assignment '=' operator.
```
my_num = 2 #stores 2 in my_num
print(my_num)

>>> 2
```
Variables can hold many types of data.
```
my_class= "python programming"

brca1_sequence = "ATGGAGGAGGAGAGGAAGGAAGGAGAGGAGAGGAGGAAGGAAGGAAGGAGAGGAAGGAGGAGGAAGGAGGAAGGAGGAGGAGGAAGGAAGGAAGGAGGAGGAAGGAAGGAAGGAGAGGAAGGAAGGAAGGAGAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAGGAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGAAGGA" #incomplete sequence

forward_primer = "AGCTGATCGTACGATAGC"

reverse_primer = "TGCATGCTAGCTAGCTAG"

melting_temp = 60.57

is_successful = True
```

### Naming Conventions
We use lowercase and underscores to name variables in Python. 

```
human_seq, current_date, user_name, drosophila_genome, genes_from_sequencing
```

Detailed style guide at: https://peps.python.org/pep-0008/

### int
Integers are whole numbers.

```
my_num = 27
```

### float
Floats represent real numbers (numbers with a decimal point).

```
temperature = 37.5  # Temperature in Celsius
```

### char
Character refers to a single character.

```
first_letter_in_alphabet = 'a'
```


### string
Strings are sequences of characters. They are enclosed in quotes.

```
sequence1 = 'ATGCGTAC'  # DNA sequence
sequence2 = "CATGTCGA"  # DNA sequence
user_name = 'pramod aryal, phd.'  #Username
```

### bool
Booleans represent True or False values, useful in logical operations. Booleans are written without quotes.

```
seq_is_valid = True  #sequence is valid
file_exists = True  #file exists
```

## Storing data
### list

### dict

### set

### tuple

## Best Practices

Names should be meaningful

## Operators

### Arithmetic

### Relational

### Logical


## Comments

white space. Comment types, docstrings, formatting

Resources
PEP8 | Style Guide for Python https://peps.python.org/pep-0008/