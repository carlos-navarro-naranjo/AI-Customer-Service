# AI-Customer-Service
A system to rank customer support tickets by priority and route them to the appropriate department. 



Functional API: Multi-Input, Multi-Output Model

A system to rank customer support tickets by priority and route them to the appropriate department. Your model has three inputs:
-	The title of the ticket (text input)
-	The text body of the ticket (text input)
-	Any tags added by the user (categorical input, assumed here to be one-hot encoded)

Your model also has two outputs:
-	The priority score of the ticket, a scalar between 0 and 1 (sigmoid output)
-	The department that should handle the ticket (a SoftMax over the set of departments)
