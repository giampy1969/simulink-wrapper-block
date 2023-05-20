# simulink-wrapper-block
Wraps the input vector into a given hypercuboid

When the input is inside the n-dimensional box defined by the two limiting vectors Min and Max, then the output is equal to the input. When the input exceeds a limit along one dimension, the output reappears "on the other side" of the box, along the same dimension.

This block is especially useful if you want to keep the evolution of a given variable in a certain range, for example, when displaying images with the virtual reality toolbox, it is better to keep the object positions within certain limits, otherwise numerical problems may prevent a correct visualization.
