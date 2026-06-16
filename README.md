# Python-Series
All Python Concepts

## Summary of Topics Covered

This notebook covers a wide range of fundamental Python programming concepts and data science libraries. Here's a breakdown of the topics you've explored:

### DAY 1: Introduction to Python
*   Basic input/output using `input()` and `print()`
*   String manipulation and `len()` function

### DAY 2: Basic Operations
*   Simple calculator: input, type casting (`int()`), addition
*   E-commerce cart simulation: input, quantity, price, total calculation

### DAY 3: Data Structures - Lists, Tuples, Sets
*   **Lists:** mutable sequences, creation, type checking, indexing, slicing, `append()`, `remove()`, `pop()`, `sort()`
*   **Tuples:** immutable sequences, creation, type checking, indexing, slicing, type casting (list to tuple, tuple to list)
*   **Sets:** unordered collection of unique items, creation, set operations (`union`, `intersection`, `difference`, `symmetric difference`)
*   **Mini Project:** Grocery List Manager (using sets to remove duplicates)

### DAY 4: Dictionaries
*   **Key Characteristics:** unordered, mutable, unique keys, any value type
*   **Dictionary Functions:** `get()`, `keys()`, `values()`, `items()`, `clear()`, `pop()`
*   Adding and updating elements
*   Nested Dictionaries
*   `update()` method

### DAY 5: Conditional Statements
*   `IF`, `ELSE`, `ELIF` conditions
*   Nested `IF` conditions
*   Ternary operator
*   **Mini Project:** Check if a number is even or odd

### DAY 6: Loops
*   **FOR Loop:** iterating over lists, dictionaries, `range()` function, `continue`, `break` statements
*   **WHILE Loop:** counting up/down, summing numbers, multiplication table, factorial calculation, reversing a string
*   **Mini Project:** Number Guessing Game

### DAY 7: Functions
*   Defining functions
*   Arbitrary Arguments (`*args`)
*   Returning multiple values
*   Time-based greeting function (using `datetime` module)
*   **Mini Project:** Simple Calculator (using functions for add, subtract, multiply, divide)
*   **Lambda Functions:** anonymous functions, single expression, multiple arguments
*   **`map()`:** applying functions to iterables (with lambda)
*   **List Comprehensions:** concise list creation, filtering, and transformation
*   **`filter()`:** filtering elements from iterables (with lambda)
*   **`reduce()`:** (from `functools`) applying a function cumulatively to items (max, min, sum, concatenation)

### DAY 8: Modules, File Handling, Error Handling, and Libraries

#### Handling Files
*   Reading and writing text files (`open()`, `read()`, `write()`, `with open() as file:`, `readline()`)
*   Working with CSV files (`csv` module, `csv.reader()`, `csv.writer()`, `writerow()`, `DictReader()`, appending data)
*   Working with JSON files (`json` module, `json.dump()`)

#### Error and Exception Handling
*   `try`, `except`, `else`, `finally` blocks
*   Common error types: `ZeroDivisionError`, `FileNotFoundError`

#### Modules and Packages
*   `math` module (`ceil()`, `floor()`)
*   `datetime` module (`datetime.now()`, `strftime()`, `strptime()`, calculating age, remaining days until birthday)
*   `os` module (`getcwd()`)
*   **Mini Project:** Date processing from CSV

### OOP - Object-Oriented Programming
*   **Class:** blueprint for objects
*   **Object:** instance of a class
*   `self` keyword
*   `__init__()` constructor method
*   Examples: `Person`, `Car`, `Account` classes (debit, credit, get balance)

### Numpy Library
*   Introduction to `numpy` for numerical computation
*   `np.array()`: creating arrays
*   `type()`, `shape` attribute
*   Mathematical functions: `np.mean()`, `np.std()`, `np.median()`
*   Indexing and slicing arrays (1D, 2D, 3D)
*   `np.ones()`
*   `reshape()`: changing array dimensions
*   `np.concatenate()`: joining arrays
*   **Mini Project:** Temperature Data Analysis (generating random data, calculating stats, filtering)

### Pandas Library
*   Introduction to `pandas` for data manipulation
*   `pd.DataFrame()`: creating DataFrames
*   Reading CSV (`pd.read_csv()`) and Excel (`pd.read_excel()`) files
*   `head()`, `info()`, `columns` attributes
*   Sorting: `sort_values()`, `sort_index()`
*   Column selection and filtering data (Boolean indexing)
*   `loc` and `iloc` for data slicing
*   `set_index()`: setting DataFrame index
*   Saving data to CSV (`to_csv()`)
*   **Data Cleaning:**
    *   `duplicated()`, `drop_duplicates()`
    *   Handling `NaN` values: `isnull().sum()`, `dropna()`, `fillna()`
    *   Changing data types (`astype()`)
    *   Renaming columns (`rename()`)
*   **Merging and Joining DataFrames:**
    *   `pd.merge()`: combining based on common columns (`inner` join)
    *   `.join()`: combining based on index
    *   `pd.concat()`: combining DataFrames (row-wise `axis=0` or column-wise `axis=1`)
*   **`GROUP BY` Operations:** `groupby()`, `agg()` (sum, count, mean)
*   **Walmart Analysis:** filtering, sorting, and grouping sales data

### Matplotlib Library
*   Basic plotting: `plt.plot()`, `plt.title()`, `plt.xlabel()`, `plt.ylabel()`
*   Line charts (sales trends)
*   Bar charts (`plt.barh()`)
*   Histograms (`plt.hist()`, `np.random.randn()`, `np.random.randint()`)
*   Pie charts (`plt.pie()`, `explode`, `autopct`, `shadow`)
*   Area plots (`plt.fill_between()`)

### Seaborn Library
*   Enhanced data visualization
*   Loading example datasets (`car_crashes.csv`, `flights.csv`, `iris.csv`, `taxis.csv`, `tips.csv`)
*   Scatter plots (`sns.scatterplot()`, `hue`, `style`)
*   Histograms (`sns.histplot()`, `kde`)
*   Box plots (`sns.boxplot()`)
*   Violin plots (`sns.violinplot()`, `hue`)
*   Pair plots (`sns.pairplot()`)
*   Heatmaps (`sns.heatmap()`, `corr()`, `annot`, `cmap`)
