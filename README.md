<img width="1196" height="527" alt="image" src="https://github.com/user-attachments/assets/1691c891-6d3d-4185-8af5-b8d4f7b4f73f" />



Website: https://numpy.org

some exciting memes related to this 😁😂😂🤣:

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="640" height="412" alt="image" src="https://github.com/user-attachments/assets/34c7db47-d2ad-43cb-acdf-f9b2efeb259c" />
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<img width="1080" height="1187" alt="image" src="https://github.com/user-attachments/assets/c260c088-0b30-4317-b1e8-843a00fc0511" />

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="442" height="720" alt="image" src="https://github.com/user-attachments/assets/02647bab-f0e7-4175-b134-0e8ae51339a7" />




----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# numpy-in-python
NumPy is a Python library used for working with arrays. It also has functions for working in the domains of linear algebra, the Fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant. It is an open-source project, and you can use it freely. NumPy stands for Numerical Python.
 Numpy is a popular library for numerical computing in Python. One of its most powerful features is its ability to work with arrays. In this guide, we’ll cover everything you need to know about Numpy arrays in Python, including how to create them, manipulate them, and perform operations on them.

Arrays have several advantages over lists in Python, including:

Arrays are optimized for numerical computations and can perform operations much faster than lists.
Arrays can be multi-dimensional, whereas lists are one-dimensional.
Arrays can only contain elements of the same data type, which makes them more memory-efficient than lists.
Arrays can be created with specific sizes and values using Numpy functions, which can save time when working with large datasets.

What are Numpy Arrays?
In Python, an array is an ordered collection of elements, each of the same data type. Numpy arrays are a specific type of array that are optimized for numerical computations. They are more powerful than Python’s built-in arrays and offer a wide range of functions for working with data.

Creating Numpy Arrays
To create a Numpy array, you can use numpy.array() function. Here’s an example:

import numpy as np

a = np.array([1, 2, 3])
print(a) 
Output:

[1 2 3] 
You can also create multi-dimensional arrays by passing in nested lists:

import numpy as np

b = np.array([[1, 2], [3, 4]])
print(b) 
Output:

[[1 2]
 [3 4]] 
Numpy also provides other functions for creating arrays, such as numpy.zeros(), numpy.ones(), and numpy.arange(). These functions are useful when you need to create arrays of specific sizes or with specific values.

Manipulating Numpy Arrays
One of the most powerful features of Numpy arrays is their ability to be manipulated with ease. Here are some common ways to manipulate Numpy arrays:

Indexing
You can access individual elements of a Numpy array using indexing. For example:

import numpy as np

a = np.array([1, 2, 3])
print(a[0])  # Output: 1 
You can also use slicing to access a subset of the array:

import numpy as np

a = np.array([1, 2, 3, 4, 5])
print(a[1:4])  # Output: [2 3 4] 
Reshaping
You can change the shape of a Numpy array using the reshape() function. For example:

import numpy as np

a = np.array([1, 2, 3, 4, 5, 6])
b = a.reshape((2, 3))
print(b) 
Output:

[[1 2 3]
 [4 5 6]] 
Transposing
You can transpose a Numpy array using the transpose() function. For example:

import numpy as np

a = np.array([[1, 2], [3, 4]])
b = a.transpose()
print(b) 
Output:

[[1 3]
 [2 4]] 
Concatenation
You can concatenate Numpy arrays using the concatenate() function. For example:

import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
c = np.concatenate((a, b))
print(c) 
Output:

[1 2 3 4 5 6] 
Operations on Numpy Arrays
Numpy arrays can be used to perform a wide range of mathematical operations. Here are some examples:

Element-wise Operations
You can perform element-wise operations on Numpy arrays using arithmetic operators. For example:

import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
c = a + b
print(c) 
Output:

[5 7 9] 
Dot Product
You can perform a dot product on Numpy arrays using the dot() function. For example:

import numpy as np

a = np.array([[1, 2], [3, 4]])
b = np.array([[5, 6], [7, 8]])
c = np.dot(a, b)
print(c) 
Output:

[[19 22]
 [43 50]] 
Conclusion
In this guide, we covered the basics of Numpy arrays in Python. We learned how to create and manipulate arrays, and how to perform operations on them. Numpy arrays are a powerful tool for numerical computing and can be used in a wide range of applications. With this knowledge, you’ll be well on your way to mastering Numpy arrays in Python.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------


The tools that I have used in this are:
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. VS CODE: https://code.visualstudio.com/
2. NUMPY OFFICIAL WEBSITE: https://numpy.org
3. CHATGPT FOR CLEARING CONFUSION AND UNDERSTANDING BETTER: https://chatgpt.com/
4. YOUTUBE VIDEO and tutorials which I USED AS A RESOURCE TO STUDY(BEGINNER): https://youtu.be/VXU4LSAQDSc?si=JugheyKhfR17_R0E, https://youtu.be/Rbh1rieb3zc?si=ZMVLbx8tPGHmxWu7
5. Website that I use to practice questions:
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Testing to test numpy:

NumPy requires pytest and hypothesis. Tests can then be run after installation with:

python -c "import numpy, sys; sys.exit(numpy.test() is False)"
