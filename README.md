# Computer-Programming-2_Final-Project

What kind of system are we building?

CALCULATOR APPLICATION SYSTEM

Calculator class have a lot 
of variables, fields and it 
is also the main class for 
the project. This class 
contains the application’s 
frame width, height, 
background color, labels of 
buttons and the co-ordination 
of each buttons.

SpecialButton class is responsible
for the buttons “backspace” , “clear”
, “clear entry”. ActionEvent method is used 
for this operation, the listener interface
for receiving action events. The class that
is interested in processing an 
action event implements this interface,
and the object created with that class is
registered with a component, using 
the component's addActionListener method. 
When the action event occurs, that object's
actionPerformed method is invoked.

DigitButton class contains the height and width of the 
button “+”, “-”,”\”,”*”, “+/-”, “.”. isInString is used 
,this function will search a target string for a matching 
string or character and return its position. This 
function allows searching for a specific character. Also 
ActionEvent is used to receive and process the operations 
in this class.

MemoryButton class is dependent to the main class and the 
Calculator class to this since it is where the history of 
the computation is stored. This includes here the functions 
of “MR” – memory recall, “MC”- memory clear, “M+”- memory 
plus, and “MS” – memory store. ActionEvent method is 
applied in this class to perform the operations.

The OperatorButton class is where the operator buttons 
addition, multiplication, subtraction, division, square 
root, percentage and fatorial are stored, by using the 
ActionEvent method, once the operator buttons is used, the 
computation will be process.
The relationship between this classses is Composition where 
each class is dependent to one another. They cannot run or 
process independently since each of them have the same 
operators and fields that is connected in order to 
successfully run a program.
