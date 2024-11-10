# Hello_world
This repository is for practicing the GitHub Flow.
New version of the branch created
import tkinter as tk
from datetime import datetime

# Get today's date in the format Day, Month, Year
today = datetime.today().strftime('%A, %B %d, %Y')

# Set up the tkinter window
root = tk.Tk()
root.title("Today's Date")
root.configure(bg='black')

# Create a label with today's date and set the text color to white
label = tk.Label(root, text=today, font=('Helvetica', 20), fg='white', bg='black')
label.pack(padx=20, pady=20)

# Set window size
root.geometry('400x200')

# Run the GUI application
root.mainloop()
