![unicorn language logoofficiel_transparent](https://github.com/user-attachments/assets/b57fa061-4a7b-4c28-b7bc-9afce40859a0)

> I created **`Unicorn language`** to create quickly GUI interface for IA Services. You can use Unicorn also to create GUI for game, audio, machine learning, health solutions, etc.
> No need to know Python or specific library. Solutions created with Unicorn can be run on linux, windows, macos, shellbotsos, and cloud platforms (azure, amazon, etc.).

Unicorn translate his code in real time to python/dearpygui library code that display the results.



# Unicorn - Documentation and Tutorials

## Versions history

## Architecture

## Tutorials


## Documentation
### objects function
** _optional_   

   
**`label`**   
_Create a label._
- **parent :** window
- **parameters :**
  - text (string) : Text of label
- **example :**   
`label "Register New Account"`

**`input`**   
_Create an input._
- **parent :** window
- **parameters :**
  - label (string) : label of input
  - variable= (variable) : name of variable to store value
  - password= (boolean) : True or False, Indicate if input is a password to protect display
- **example :**   
`input "Username" variable=username` 
`input "Password" variable=password password=True` 

   
**`window`**   
_Create a window to integrate all Unicorn object type._
- **parent :** none
- **parameters :**
  - label : label of window
  - width : width in pixels _**_
  - height : height in pixels _**_
- **example :**   
`window "User Registration" width=400 height=300 :` 





