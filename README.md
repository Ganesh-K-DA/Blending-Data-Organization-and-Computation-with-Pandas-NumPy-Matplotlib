

# Blending-Data-Organization-and-Computation-with-Pandas-NumPy-Matplotlib


### PANDAS:
Pandas is a powerful Python library for data manipulation and analysis. It provides data structures like Series (1D) and DataFrame (2D) to handle and process structured data efficiently.

🔹 Key Features of Pandas:
* Easy handling of missing data
* Powerful data filtering and selection
* Grouping and aggregation (groupby)
* Merging and joining datasets (merge, join)
* Reading/writing data from multiple formats (CSV, Excel, SQL, JSON, etc.)
* Fast operations on large datasets

## INSTALATION OF PANDAS:
![Image](https://github.com/user-attachments/assets/3ff6b2fb-b7c5-4757-8526-da78d847e8b9)

## Import Pandas:
![Image](https://github.com/user-attachments/assets/b2cf9815-f6d4-401c-9768-ea18f1934093)

## Data Structures: - Series: One dimensional array. Hold any datatypes (integers, strings, float etc.):

![Image](https://github.com/user-attachments/assets/ba63ba62-24b8-4ca4-97f6-22f06edff996)

## Data frame: A data frame is two dimensional table -like data structure with rows and columns. It similar to a spreadsheet or SQL table:

![Image](https://github.com/user-attachments/assets/eeede5a2-71ba-4bd4-ae12-0fef73b0f862)

## Accessing Data:

![Image](https://github.com/user-attachments/assets/d127b98e-c29b-4406-bfdb-ae600b2709bf)
![Image](https://github.com/user-attachments/assets/a4360127-a301-4ada-b8fc-775608ba920b)
![Image](https://github.com/user-attachments/assets/1307a4a8-d8dc-44a6-9a59-aa53a59c8317)

## Adding new column:- Mentioned the new column name and also update the value:

![Image](https://github.com/user-attachments/assets/ca3465bc-28f5-4d8a-b5dd-7d1060223fbe)

## Describe:
The output of the describe() function applied to a DataFrame column named "Age" in Python .
### Here’s a breakdown of the output:

* count: 3 → There are three entries in the "Age" column.
* mean: 30.0 → The average age is 30.
* std: 5.0 → The standard deviation is 5.
* min: 25.0 → The minimum age is 25.
* 25% (First Quartile - Q1): 27.5 → 25% of the values are below 27.5.
* 50% (Median - Q2): 30.0 → The median value is 30.
* 75% (Third Quartile - Q3): 32.5 → 75% of the values are below 32.5.
* max: 35.0 → The maximum age is 35.

![Image](https://github.com/user-attachments/assets/3ea1bb6f-7f35-49ac-87ec-ac63a3b522df)

## Import Data Location Path from Local:

![Image](https://github.com/user-attachments/assets/161ec2a0-3101-48e2-a415-d186c9cf7f47)

## Saving or Loading data:- Choose the read file type according to the file type of local:

![Image](https://github.com/user-attachments/assets/bcd33d9e-2e6e-4bab-bafc-0c6e359d5e1a)

## Change all the ‘\’to ‘/’ 

![Image](https://github.com/user-attachments/assets/e94ce3be-c6e3-4071-8db7-45251b6f856f)


## Numpy:
NumPy is a powerful Python library used for numerical computing. It provides support for multi-dimensional arrays, mathematical functions, linear algebra, and more. 
### Some key features include:

* ndarray: A fast, flexible multi-dimensional array object.
* Broadcasting: Enables operations on arrays of different shapes.
* Vectorized Operations: Faster computations compared to Python loops.
* Linear Algebra: Built-in functions for matrix operations.
* Random Sampling: Tools for generating random numbers.
* Integration with Other Libraries: Used in SciPy, Pandas, TensorFlow, etc.

## How to Install Numpy:

![Image](https://github.com/user-attachments/assets/b47b241f-eb0a-4c0a-bd1f-d7c1ee1c43b2)

## Importing Numpy:

![Image](https://github.com/user-attachments/assets/974b1e83-9ac4-49bd-9341-92c1e5f62a88)

## To Check Numpy Functions:

 ![Image](https://github.com/user-attachments/assets/3679595a-8db8-4cac-95e3-7659eef8d20a)

## Array:- Array is a Collection of Elements np.array:

![Image](https://github.com/user-attachments/assets/9daad3ad-879d-4f2f-b6bb-f90dc6150dbb)

## np.zeros :

![Image](https://github.com/user-attachments/assets/5c0121ab-64db-4946-9ddc-4505066a8a5c)

## This looks like a 5x8 matrix filled with zeros, which is a great way to initialize arrays for numerical computations or placeholder data.
### np.ones:

![Image](https://github.com/user-attachments/assets/f7bc87c4-c752-4b2c-a29c-64e05946ed47)

## one-dimensional array, and it's likely you're exploring operations with arrays.
### Here's how you can create it using NumPy: python

![Image](https://github.com/user-attachments/assets/1f5ac371-d381-43ac-a539-5a14af733818)

## One & Two Dimensional Array How it Works:

![Image](https://github.com/user-attachments/assets/653d1110-ceb7-4c36-aff9-9d99423d2f1b)

## Finding the Numarical Operators the below Table shows how the Operators works:

![Image](https://github.com/user-attachments/assets/f6b4c47b-357f-4339-92cd-4d2082b8d573)

## Mathematical Operators:

![Image](https://github.com/user-attachments/assets/8b387a45-aafe-4406-99b0-fc25d8efefbf)

* Addition: NumPy performs element-wise addition. If the arrays have the same shape, corresponding elements are added.
* Subtraction: Element-wise subtraction is performed. Each element of the first array is subtracted by the corresponding element of the second array.
* Multiplication: NumPy performs element-wise multiplication, which multiplies corresponding elements together.
* Division: NumPy divides elements of the first array by the corresponding elements of the second array.

## SUM, MAX, MIN, VARIANCE, MEAN, and STANDARD DEVIATION:
These are the statistical functions or descriptive statistics in mathematics and data analysis. They are used to summarize and analyze numerical data.
* Sum: Adds all elements together.
* Max: Finds the largest value in the array.
* Min: Finds the smallest value in the array.
* Variance: Measures the spread of the data.
* Sum Array: computes the sum of elements in an array, either across all elements or along a specified axis in the case of multidimensional arrays.

![Image](https://github.com/user-attachments/assets/944d1551-30d5-4999-839d-835a4db6f975)

## Logical Operator:
Logical operators are used to perform logical operations, often in conditions and decision-making. 
* Greater Than (>) Operator : Checks if the left value is greater than the right value.
* Equal To (==) : Checks if two values are equal.
* Less Than or Equal To (<=) : Checks if the left value is less than or equal to the right value.

![Image](https://github.com/user-attachments/assets/553434fa-b390-447c-8e91-08333d6af835)

The above image show's how the operators works.

## Vstack Array:
In NumPy, vstack (vertical stacking) is used to stack arrays vertically, meaning along the first axis (axis=0). It combines arrays into a single array where the arrays are added as new rows.

![Image](https://github.com/user-attachments/assets/28945634-ba5a-48a7-9017-f042b0c15a2b)

This combines all the arrays vertically (adding each as a new row) into a 2D array.

## Hstack:
The hstack function in NumPy horizontally stacks arrays, meaning it joins arrays along the second axis (axis=1 for 2D arrays). It appends arrays side by side, provided they are compatible in dimensions.

![Image](https://github.com/user-attachments/assets/4e40b695-7d2e-4f02-abf6-b4f6bc9d7a49)

This combines all the arrays Horizontally.

## Dstack:
In NumPy, dstack (depth stacking) is used to stack arrays along the third dimension. This means the arrays are added "depth-wise," creating a 3D array. It's commonly used when you need to combine arrays into layers.

![Image](https://github.com/user-attachments/assets/f1e11404-fdda-45c1-aa0e-a4846dfa0da4)

It is useful for combining multiple 2D arrays into a single 3D array.

## Concatinate:
In NumPy, concatenation refers to joining two or more arrays along an existing axis.

![Image](https://github.com/user-attachments/assets/c7277ab0-f81d-4acf-b35a-df135688d27f)

* axis=0: Combines arrays vertically (adds rows). The number of columns must match. 
* axis=1: Combines arrays horizontally (adds columns). The number of rows must match.

##  SPLITTING:
Splitting refers to dividing an array into multiple subarrays.

### Following shows the splitting: 
#### Split, Vsplit, Hsphit:
* Split: Splits an array into multiple subarrays along a specified axis.
* Hsplit (Horizontal Split): Splits an array into subarrays along the columns.
* Vsplit (Vertical Split):Splits an array into subarrays along the rows.

![Image](https://github.com/user-attachments/assets/3729d130-5e6d-469c-bf86-f653ba21f7c3)

The above image shows that how the split works.

# Matplotlib in Python:

Matplotlib is a widely used data visualization library in Python that allows you to create a variety of static, animated, and interactive plots. It is particularly useful for creating charts, graphs, and figures for data analysis.

### Uses of Matplotlib:
* Data Analysis & Exploration – Helps in understanding data patterns and distributions.
* Scientific & Engineering Applications – Used in research for plotting graphs of equations.
* Machine Learning & AI – Visualizes model performance and comparisons.
* Business & Financial Analysis – Helps in presenting reports and dashboards.
* Real-time Data Monitoring – Used for tracking trends in various domains. 

#### Install Matplotlib in VS Code:- Use the code “pip install matplotlib:

![Image](https://github.com/user-attachments/assets/d165dafe-5694-46a6-87ed-6f2a63d80444)

#### Working area of the VS Code write :” import matplotlib.pyplot as plt”

![Image](https://github.com/user-attachments/assets/f135addb-4cd4-4b6b-b1e8-919c76c91603)


### Here are some key types:
* Line Plot – Shows trends over time.
* Bar Chart – Compares quantities across categories.
* Histogram – Shows distribution of a dataset.
* Pie Chart – Displays parts of a whole.
* Scatter Plot – Shows relationships between two variables.
* Box Plot – Shows distribution, median, and outliers.
* Heatmap – Uses color to represent values in a matrix.
* Area Chart – Like a line plot but filled below the line.
* Violin Plot – Similar to a box plot but shows distribution density.
* Bubble Chart – Scatter plot with a third variable shown as bubble size.


### Line Plot – Shows trends over time:
it is used to show trends over time or continuous data.

![Image](https://github.com/user-attachments/assets/a34c14dc-282e-4113-8a2f-8672b2421cd7)
![Image](https://github.com/user-attachments/assets/a1f992d8-9ee5-4eab-9b12-37ea2506e0b6)

### Bar Chart – Compares quantities across categories:
it is used to compare categorical data.

![Image](https://github.com/user-attachments/assets/1e75fa62-2efe-4dea-992c-5ab909637845)
![Image](https://github.com/user-attachments/assets/3aa2265c-19f3-451f-b3d6-e3c1c7e6c800)

### Histogram – Shows distribution of a dataset:
it is used to show the distribution of numerical data.

![Image](https://github.com/user-attachments/assets/5c203233-503f-44ef-970c-ad2457fe67fa)
![Image](https://github.com/user-attachments/assets/55a7f4cf-5d42-4b46-a0fa-63b1e9438421)

### Scatter Plot – Shows relationships between two variables:
it is used to show relationships between two variables.

![Image](https://github.com/user-attachments/assets/5b6bb5d7-01f8-4c95-88b7-6d7a461a88ec)
![Image](https://github.com/user-attachments/assets/a7209fa5-901a-4664-a5f7-04ff7d902242)

### Pie Chart – Displays parts of a whole:
it is used to show proportions of a whole.

![Image](https://github.com/user-attachments/assets/7d01c026-3b3c-42dd-822d-71320d9b04bb)
![Image](https://github.com/user-attachments/assets/622fac04-809e-4608-b3a7-4fea326ad7bc)

### Box Plot – Shows distribution, median, and outliers:
it is used to show the distribution of numerical data.

![Image](https://github.com/user-attachments/assets/7081589c-f1f9-4786-ac5e-daa4ea374fbb)
![Image](https://github.com/user-attachments/assets/4dfb651f-b95f-41d4-9ecd-d9e95a3a5194)

### Area Chart – Like a line plot but filled below the line:
it is used to show how different parts contribute to a total over time.

![Image](https://github.com/user-attachments/assets/c10288a2-bd8d-4aca-b180-05f7d15dbe25)
![Image](https://github.com/user-attachments/assets/52168609-bd0b-4e77-86e6-b4fee418918c)

### Heatmap – Uses color to represent values in a matrix:
it is used to visualize correlation between variables.

![Image](https://github.com/user-attachments/assets/673d7d7a-d9fa-46f8-937a-f71b3a30d554)
![Image](https://github.com/user-attachments/assets/d1105a15-8e15-4c30-b761-4b9e81958645)

### Error Bar - used to display the variability or uncertainty in data:
it is used to show uncertainty or variability in data.

![Image](https://github.com/user-attachments/assets/5a89f0e0-606e-40ea-853c-4df0ef2dec3c)
![Image](https://github.com/user-attachments/assets/8e537378-b917-482a-8873-78cd5b44c5e8)

### Polar Plot - Represents data in terms of angle (θ) and radius (r):
it is used to visualize data in circular format.

![Image](https://github.com/user-attachments/assets/718a1473-31f6-4bde-9dc4-952092db3826)
![Image](https://github.com/user-attachments/assets/db057496-9f58-463c-968c-5a80ab07f485)

### Step Plot - The line forms steps, rather than diagonal lines between points:
it is used for discrete changes in data.

![Image](https://github.com/user-attachments/assets/c05b2674-0ee8-4618-bbd9-118e176ea4d0)
![Image](https://github.com/user-attachments/assets/2abc61ca-8f60-44c8-a79e-2deb76f13242)

### Violin Plot – Similar to a box plot but shows distribution density:
it is used to show the distribution of the data along with probability density.

![Image](https://github.com/user-attachments/assets/97d83223-005d-4c6c-9b85-3fb2fd302218)
![Image](https://github.com/user-attachments/assets/c3eb2b8f-0555-4d9e-97d4-c9aa1f495376)

### Bubble chart - like a scatter plot with a twist :
it adds a third dimension of data using the size of the bubbles.

![Image](https://github.com/user-attachments/assets/b85a5eec-5ecc-4cee-be0a-8db583af9448)
![Image](https://github.com/user-attachments/assets/42b5d70e-82bb-4682-823e-51de5df8f0f5)

### 3D Plot — a solid way to visualize relationships in three dimensions:
Perfect when you want to go beyond 2D scatter or line plots and really show how data behaves across a surface or volume.

![Image](https://github.com/user-attachments/assets/9bfcc432-af67-4c74-b283-dd379a4b89bc)
![Image](https://github.com/user-attachments/assets/164f9dee-3e93-4f5a-80d1-eb8f18ba2bce)



## Conclusion:
Matplotlib offers multiple types of plots for various data visualization needs.
