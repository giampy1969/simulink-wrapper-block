# simulink-wrapper-block
Wraps the input vector into a given hypercuboid

[![View Closed Universe on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/9096-closed-universe)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=giampy1969/simulink-wrapper-block)

When the input is inside the n-dimensional box defined by the two limiting vectors Min and Max, then the output is equal to the input. When the input exceeds a limit along one dimension, the output reappears "on the other side" of the box, along the same dimension.

This block is especially useful if you want to keep the evolution of a given variable in a certain range, for example, when displaying images with the virtual reality toolbox, it is better to keep the object positions within certain limits, otherwise numerical problems may prevent a correct visualization.
