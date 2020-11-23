# saturated 
with the method from Lin, I try to deal with saturation of DMSP/OLS. But it didn't work. Or in other words, the outcome data isn't good enough  as my research data.  And if you are also interested in the research or want to use nighttime light value to do something, we could get some talk.
#reference 
Lin Ma, Jiansheng Wu, Weifeng Li,等. Evaluating Saturation Correction Methods for DMSP/OLS Nighttime Light Data: A Case Study from China’s Cities[J]. Remote Sensing, 2014.
#details 
I use the regional method mentioned in the paper. I employ cubic function to fit un-saturation part(0-62), and reject the saturation part( above 63) by the cubic function. Maybe the problem is the image of city which part is different from the paper. I use the center point of the city as the center of rectangle and the square(the size of city) as the length of side. But the paper use arcgis to get city image.


And the analysis of the result put into the doc.
