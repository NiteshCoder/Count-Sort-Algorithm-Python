# Count-Sort-Algorithm-Python
Count Sort Algorithm Code in Python with explicit way.

- One of the fastest sorting algorithm for sorting elements.

- Step 1 : Find the maximum 
- Step 2 : Make new array with size = maximum
- Step 3 : Initialise new array element with 0.
- Step 4 : Go to Original Array. 
- Step 5 : As per Original Array value put 1 or 0 in new array
- Step 6 : Fetch the elements from new array one by one As per index.

-Example :
	
- Original_ = 3 1 9 7 1 2 4
- Max_Value = 9
- new array = 0 0 0 0 0 0 0 0 0

------------------------------------------------------------
- Original[0] = 3 // so put new array[3] = 1
- Original[1] = 1 // so put new array[1] = 1
- Original[2] = 9 // so put new array[9] = 1
- Original[3] = 7 // so put new array[7] = 1
- Original[4] = 1 // so put new array[1] = 2 // we got 1 two time that's Why we Increment.
- Original[5] = 2 // so put new array[2] = 1
- Original[6] = 4 // so put new array[4] = 1

--------------------------------------------------------------
- Now new array = 0 2 1 1 1 0 0 1 0 1
---------------------------------------------------------------
- Sorting.
- Fetch values from new_array if 2 then we will get two same values.
- if 1 then simply put its index.
- If 0 nothing to do just go ahed.

THANK YOU.

