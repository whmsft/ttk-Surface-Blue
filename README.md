# Surface Blue, a theme for ttk
## theme made with inspiration from Azure ttk theme and the short lived Metro Surface UI
![image](https://user-images.githubusercontent.com/72214351/124927330-25a1d100-e01c-11eb-9816-b0fe45b95623.png)

### How to use it?
Python - tkinter:
```python3
# Import the tcl file
root.tk.call('source', 'Surface-blue.tcl')

# Set the theme with the theme_use method
ttk.Style().theme_use('surface-blue')
```

Tcl/tk:
```tcl
# Import the tcl file
source "Surface-blue.tcl"

# Set theme using the theme use method
ttk::style theme use surface-blue
```

EXTRA ELEMENT:
- Switch:
```python3
switch = ttk.Checkbutton(root, text='Switch', style='Switch', variable=var)
```
image:
![image](https://user-images.githubusercontent.com/72214351/124929443-23407680-e01e-11eb-847f-04e10b5f2c70.png)


Credits:
- me (for the whole theme)
- Paint.net (for the software on which the images are designed.)
- rdbende (for the Azure-ttk-Theme on which this is theme is based on.)
- Microsoft (for Windows and Metro UI.)
- Advanced Installer (for the idea which made me make this theme.)
