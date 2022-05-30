### List

`l = []` &nbsp; &nbsp; &nbsp; # Type List  

>`list = [1, 2, 3, 4, 5]`  
>&nbsp;  
>list &nbsp; &nbsp; &nbsp; # Accessing List
>>Output:  
>>&nbsp;  
>>[1, 2, 3, 4, 5]

&nbsp;  
*Like strings, lists can be indexed and sliced.*

`list = [1, 2, 3, 4, 5]`

>list[0] &nbsp; &nbsp; # element in position 0
>>1  &nbsp; # Output

>list[-1]  &nbsp; &nbsp; # element in last position
>>5 &nbsp; # Output

>list[-3:] &nbsp; &nbsp;  # slicing returns a new list
>>[3, 4, 5] &nbsp; # Output

&nbsp;  
*Lists also support operations like concatenation.*

`list = [1, 2, 3, 4, 5]`  

>list + [6, 7, 8, 9, 10]
>>[1, 2, 3, 4, 5, 6, 7, 8, 9, 10] &nbsp; # Output

&nbsp;  
*lists are a mutable type, i.e. it is possible to change their content*  

`list = [1, 2, 3, 4, 5]`

>list[2] = 7
>>[1, 2, 7, 4, 5] &nbsp; # Output
