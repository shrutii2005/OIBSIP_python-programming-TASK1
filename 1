import tkinter as tk
from tkinter import messagebox
import random
import string
import pyperclip

def generate_password():
    try:
        length = int(length_entry.get())
        use_letters = letters_var.get()
        use_numbers = numbers_var.get()
        use_symbols = symbols_var.get()

        characters = ""
        if use_letters:
            characters += string.ascii_letters
        if use_numbers:
            characters += string.digits
        if use_symbols:
            characters += string.punctuation

        if not characters:
            messagebox.showerror("Error", "Select at least one character type!")
            return

        password = ''.join(random.choice(characters) for _ in range(length))
        result_entry.delete(0, tk.END)
        result_entry.insert(0, password)
    except ValueError:
        messagebox.showerror("Invalid input", "Please enter a valid number.")

def copy_to_clipboard():
    password = result_entry.get()
    if password:
        pyperclip.copy(password)
        messagebox.showinfo("Copied", "Password copied to clipboard!")

# --- GUI Setup ---
root = tk.Tk()
root.title("Password Generator")
root.geometry("400x250")
root.resizable(False, False)

# --- Widgets ---
tk.Label(root, text="Password Length:").pack(pady=5)
length_entry = tk.Entry(root)
length_entry.pack()

letters_var = tk.BooleanVar(value=True)
numbers_var = tk.BooleanVar(value=True)
symbols_var = tk.BooleanVar(value=False)

tk.Checkbutton(root, text="Include Letters", variable=letters_var).pack(anchor='w', padx=20)
tk.Checkbutton(root, text="Include Numbers", variable=numbers_var).pack(anchor='w', padx=20)
tk.Checkbutton(root, text="Include Symbols", variable=symbols_var).pack(anchor='w', padx=20)

tk.Button(root, text="Generate Password", command=generate_password).pack(pady=10)

result_entry = tk.Entry(root, width=40, font=('Arial', 12))
result_entry.pack(pady=5)

tk.Button(root, text="Copy to Clipboard", command=copy_to_clipboard).pack()

root.mainloop()
