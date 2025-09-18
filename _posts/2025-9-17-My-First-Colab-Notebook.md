# My First Google Colab Notebook!
"""

import matplotlib.pyplot as plt
import numpy as np

# Define the function
def f(x):
    return x**2

# Generate x values from -10 to 10
x = np.linspace(-10, 10, 400)

# Compute y values
y = f(x)

# Create the plot
plt.plot(x, y, label='f(x) = x²', color='blue')
plt.title('Graph of f(x) = x²')
plt.xlabel('x')
plt.ylabel('f(x)')
plt.grid(True)
plt.legend()
plt.axhline(0, color='black', linewidth=0.5)  # x-axis
plt.axvline(0, color='black', linewidth=0.5)  # y-axis
plt.show()

import matplotlib.pyplot as plt
import numpy as np

# Define the functions
def f(x):
    return x**2

def g(x):
    return x**3

# Generate x values
x = np.linspace(-10, 10, 400)

# Compute y values
y1 = f(x)
y2 = g(x)

# Create the plot
plt.plot(x, y1, label='f(x) = x²', color='blue')
plt.plot(x, y2, label='g(x) = x³', color='red')

# Formatting the plot
plt.title('Graph of f(x) = x² and g(x) = x³')
plt.xlabel('x')
plt.ylabel('y')
plt.grid(True)
plt.legend()
plt.axhline(0, color='black', linewidth=0.5)  # x-axis
plt.axvline(0, color='black', linewidth=0.5)  # y-axis
plt.show()

import matplotlib.pyplot as plt
import numpy as np

# Define the functions
def f(x):
    return x**2

def g(x):
    return x**3

# Generate x values
x = np.linspace(-10, 10, 100)

# Compute y values
y1 = f(x)
y2 = g(x)

# Create the scatter plot
plt.scatter(x, y1, label='f(x) = x²', color='purple', s=10)
plt.scatter(x, y2, label='g(x) = x³', color='black', s=10)

# Formatting the plot
plt.title('Scatter Plot of f(x) = x² and g(x) = x³')
plt.xlabel('x')
plt.ylabel('y')
plt.grid(True)
plt.legend()
plt.axhline(0, color='black', linewidth=0.5)  # x-axis
plt.axvline(0, color='black', linewidth=0.5)  # y-axis
plt.show()
