### List

`list = []` &nbsp; &nbsp; &nbsp; # Type List  

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

>list[2] = 7 &nbsp; # element at index two is assigned 7 
>>[1, 2, 7, 4, 5] &nbsp; # Output

&nbsp;  
*You can also add new items at the end of the list, by using the append() method*

`list = [1, 2, 3, 4, 5]`

>list.append(6)
>>[1, 2, 3, 4, 5, 6] &nbsp; # Output

&nbsp;  
*You can also add new items at any index, by using the insert() method*

`list = [1, 2, 3, 5, 6]`

syntax: `list.insert(index,element)`

>list.insert(3,4) &nbsp; # insert item at index 3 item 4
>>[1, 2, 3, 4, 5, 6] &nbsp; # Output

&nbsp;  
*You can also remove items from the list, by using the pop() method*  

`list = [1, 2, 3, 4, 5]`

>list.pop() &nbsp; # removes the last item from the list
>>[1, 2, 3, 4]

>list.pop(2) &nbsp; &nbsp; # removes the item at index 2
>[1, 2, 4] &nbsp; #output

&nbsp;  

***Declare `list` as a list first***

***`list.press_tab_button` : shows all the available list methods***

(Note: *press_tab_button* is not a command you have to press the tab button)

&nbsp;  

***NOTE: All these commands runs in ipython*** 
