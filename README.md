# Americommerce-Wrapping-Fix
CSS to correct the wrapping issue for products in the Category and Search pages of Americommerce and by extension Bootstrap

Due to how floats and CSS wrapping works, sometimes the next row does not wrap properly under the previous row when the window is sized smaller. This corrects it for when the items are 3 across or 2 across. In Americommerce, The Base theme shows this issue with 2 products across and the UltraStore theme has this issue with 3 products across and two products across.

Broken | Fixed
------------ | -------------
![broken 3 across](/images/broken-wrapping-3-across.png) | ![fixed 3 across](/images/fixed-wrapping-3-across.png)
![broken 2 across](/images/broken-wrapping-2-across.png) | ![fixed 2 across](/images/fixed-wrapping-2-across.png)



Add the code in the .css file to the Global CSS file. 
