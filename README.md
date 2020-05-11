# Stack
What is difference between vstack and hstack  method?
 
*# Horitzontal Stack*

With hstack you can appened data horizontally. 


import numpy as np
f = np.array([1,2,3])
g = np.array([4,5,6])

print('Horizontal Append:', np.hstack((f, g)))

*Output:*

Horizontal Append: [1 2 3 4 5 6]

*Vertical Stack*

With vstack you can appened data vertically.

 import numpy as np
f = np.array([1,2,3])
g = np.array([4,5,6])

print('Vertical Append:', np.vstack((f, g)))
*Output:*

Vertical Append: [[1 2 3]
 [4 5 6]]
