# simulink-signal-byteview
Decompose numerical Simulink signals into bytes and recompose them

[![View ByteView on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/6649-byteview)

This block takes in input a vector of Ni signals belonging to a type Ti, 
puts them all in a contiguous memory zone, and reinterprets them as a vector of No signals belonging to a type To.

Typically you can use this block to decompose/recompose doubles or floats into/from the bytes that make them.

You might also be interested in https://github.com/giampy1969/simulink-udpip-blocks
