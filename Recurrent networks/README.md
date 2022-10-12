
The goal here is to make a model that given a sequence of letters or digits will output that same sequence, but with a certain delay. Let's say the input is a string 'abacaba', we want the model to not output anything for 3 steps (delay length), and then output the original string step by step, except the last 3 characters. So, target output is then 'XXXabac', where 'X' is empty output.
