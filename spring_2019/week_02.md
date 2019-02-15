## Last Week's Accomplishments

> Last week I successfully implemented labels to flip flops and other components.  I added a name attribute to all inputs and outputs and set its default value to an empty string.  Then in the components that needed names, I overrided it with the correct names.  For example, the JK flip flop would have input names J, K, and >(clock).  All flip flop components have the same labels for outputs so that was set in the flip flop parent class.  This method can be easily extended to other components as necessary. 

## This Week's Plan

> This next week I will be focusing on cleaning up the code and making it easier to read/understand.  I also will implement a switch to turn off the labels in case they slow down the rest of the program, as in the case of very large/complex circuits.  Lastly, I'm planning on changing the layout of the input terminals on the rendered object.  Currently, the labels are anchored at the top and bottom, and then evenly spaces between those.  However, this does not look as good as the earlier format, with inputs evenly spaced along the side without any on the top and bottom corners.


## Anything Blocking?

> There is not much blocking beyond my infamiliarity with the TypeScript language and project structure.  


## Notes

