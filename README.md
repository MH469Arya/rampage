Exp11
PS-Online Shopping System: Develop classes for products, customers, and shopping carts. Include methods for adding items to the cart, calculating total costs, processing orders, and managing inventory.
import tkinter as tk  # Import the Tkinter module

# Create the main application window
root = tk.Tk()
root.title("Experiment No: 12 Title: GUI")

# Title label
L1 = tk.Label(root, text="Experiment No:12 Calculate Area of Circle, Triangle and Rectangle", font=("Arial", 14))
L1.pack()

label1 = tk.Label(root, text="Enter Radius for Circle", font=("Arial", 15))
label1.pack()
entry1 = tk.Entry(root, font=("Arial", 15))
entry1.pack()

label2 = tk.Label(root, text="Enter Base and Height for Triangle", font=("Arial", 15))
label2.pack()
entry21 = tk.Entry(root, font=("Arial", 15))
entry21.pack()
entry22 = tk.Entry(root, font=("Arial", 15))
entry22.pack()

label3 = tk.Label(root, text="Enter Length and Breadth for Rectangle", font=("Arial", 15))
label3.pack()
entry31 = tk.Entry(root, font=("Arial", 15))
entry31.pack()
entry32 = tk.Entry(root, font=("Arial", 15))
entry32.pack()
