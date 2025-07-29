# 42-Norm-Cleaner
This project is to clear as the 42 norm wait it, like delete forbidden things, multiples space, ...

I try to make your code work even after all the modification, but go check your code just in case.
But if you use for functional things forbidden function your code will be break.

# All automation
## Line deletion
This program will delete line that are not conform.

### From a predefine list
Delete all lines that contains:
* Forbidden functions call
* Forbidden include line

All of theses forbidden things are defined in the folder "enums" if you want to remove some or add some you can.

### From defined rule of the Norm
Delete all line that are not conform to the Norm, here a list of line that will be deleted:
* Multiples empty lines
* Comment in function
* Empty line in function (not is its for variable declaration)

(Variable declaration are find with the type that are defined in "enums" folder, if you see bug or other, look if the type is defined in (custom type detected if prefixed with "t_"))

## Line edition
If line are not valid because of little things it will be fixed automatically, thing that are automatically fixed:
* Multiples space
* Space between functions
* Space after variable declaration
* No space in brackets or brace, ...
* Space after keyword (defined in "enums" folder also)
* Space at end of line
* Space before semi-colon
* Space around operators (conflict between pointer and multiplication)
