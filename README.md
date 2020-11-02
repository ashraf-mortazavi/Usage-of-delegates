# Usage-of-delegates
I am going to create an application which executes one of three methods (Sum, Subtract, Multiply) based on a single provided parameter  First, I will write this example without delegates and then I will refactor that code by introducing delegates.
In first method(without delegates), I will get the correct response for any operation I send to the Execute method. But this code could be much better and easier to read without switch-case expression. If I am going to have more than ten operations (for example), this switch block would be very ugly to read and maintain as well. 
Therefor, let’s change  code to make it readable, maintainable and more object-oriented. 
In second method (with delegates) I create a dictionary which will hold all the operations and all the references towards my methods (Func delegates) then I inject ExcutionManager class  into the OperationManager class and change the Execute method. At the first look, you can see how much better this code is.
