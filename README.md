Download Link: https://assignmentchef.com/product/solved-cpe-325-assignment-5
<br>



<h2>Assignment</h2>

<ol>

 <li>Write an assembly program that multiplies the corresponding elements of two arrays and stores the results in a third array. The arrays need to have at least 6 elements of varying numbers. Your program should basically implement the loop below:</li>

</ol>

for (k = 0; k &lt; array_size; k++)       array_3[k] = array_1[k] * array_2[k];

This program is responsible for initializing both input arrays, calling the two subroutines – SW_product, HW_product, and allocating the space to store the results calculated by the subroutines. This program is also responsible for passing the required input parameters and address of the memory location reserved to store the result to the subroutines using the <u>program stack</u>.

<ol start="2">

 <li>SW_product uses Shift-and-Add multiplication algorithm and HW_product uses Hardware Multiplier to multiply the elements.</li>

 <li>Determine the number of clock cycles required to evaluate the equation by each subroutine. How many elements can be evaluated using SW_product and HW_product in a sec? Explain which one is more efficient and why?</li>

 <li> Write an assembly program that passes a base number (other than 0 or 1) to a subroutine which populates an array with the first 5 powers of that base number. For instance, if you pass the number 6 to the subroutine, the result array should be populated with 6<sup>1</sup>, 6<sup>2</sup>, 6<sup>3</sup>, 6<sup>4</sup> and 6<sup>5</sup>. Create subroutines to calculate the results using software and hardware. Use Shift-and-add multiplication algorithm from part 1 and for the hardware use hardware multiplier. The parameters and results should be passed between subroutines and main program using either<u> registers or the program stack</u>.</li>

</ol>


