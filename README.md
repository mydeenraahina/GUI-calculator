<div align='center'>

<h1>THIS IS A /GUI-calculator USING PYTHON Tkinter</h1>
<p>this code is to creates a simple calculator GUI using the Tkinter library in Python. 
 Here's is the working pattern of this code:

GUI Initialization:

The code initializes a Tkinter window and sets its title to "calculator."
It creates a frame within the window with a gray background.

window = tk.Tk()
window.title("calculator")
frame = tk.Frame(master=window, bg="gray", width=50)
frame.pack()
Entry Widget:

An entry widget is added to the frame, providing a space to display and input text.
The widget has a raised relief, a border width of 20, and a width of 50 characters.

entry = tk.Entry(master=frame, relief=tk.RAISED, borderwidth=20, width=50)
entry.grid(row=0, column=3)
Number Buttons and Operations:

Buttons for digits 0-9 and various arithmetic operations are created using the tk.Button widget.
Each button is associated with a command, which is a lambda function calling the no function with the respective digit or operation as an argument.

button0 = tk.Button(master=frame, text="0", width=5, command=lambda: no(0))
# ... (Similar buttons for digits 1-9 and arithmetic operations)
Command Functions:

The no function appends the specified digit or operation to the entry widget.
The clear function clears the entry widget.
The equal function evaluates the expression in the entry widget and displays the result.

def no(n):
    entry.insert(tk.END, n)

def clear():
    entry.delete(0, tk.END)

def equal():
    try:
        y = str(eval(entry.get()))
        entry.delete(0, tk.END)
        entry.insert(0, y)
    except:
        mg.showinfo("error")
Button Placement:

The buttons are placed in the grid layout of the frame, with specific rows and columns.

button0.grid(row=2, column=1, padx=5, pady=5)
# ... (Grid placement for other buttons)
Main Event Loop:

The Tkinter main event loop (window.mainloop()) is started, allowing the GUI to handle user interactions.

window.mainloop()
The working pattern involves creating a GUI window with buttons for digits, arithmetic operations, and additional symbols. Users can interact with the calculator by clicking the buttons, and the entry widget displays the input and results. The code makes use of event-driven programming with Tkinter to respond to user actions.







<h4> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/blob/master/README.md"> Documentation </a> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/issues"> Request Feature </a> </h4>


</div>




## :star2: About the Project

## :handshake: Contact

MYDEENRAAHINA - - mydeenraahina862@gmail.com

Project Link: [https://github.com/mydeenraahina/GUI-calculator](https://github.com/mydeenraahina/GUI-calculator)
