import tkinter as tk
import webbrowser
root = tk.Tk()
menu = tk.Menu(root)
# Create a menu item for each season
for season in ["Autumn", "Winter", "Spring", "Summer"]:
    menu.add_command(label=season, command=lambda: open_link(season))
# Add the menu to the root window
root.config(menu=menu)
# Define a function to open a link in the user's browser
def open_link(season):
    webbrowser.open("https://www.planteaenverde.es/blog/como-hacer-un-huerto-urbano-en-casa-3/" + season)
# Start the main loop
root.mainloop()
hola hola hola



